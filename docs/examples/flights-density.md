<script setup>
  import { reset } from '@uwdata/vgplot';
  reset();
</script>

# Flights Density

Density `raster` and `contour` lines for 200,000+ flights by departure hour and arrival delay. The sliders adjust the smoothing (bandwidth) and number of contour thresholds.

<Example spec="/specs/yaml/flights-density.yaml" />

## Specification

::: code-group
<<< @/public/specs/esm/flights-density.js [JavaScript]
<<< @/public/specs/yaml/flights-density.yaml [YAML]
<<< @/public/specs/json/flights-density.json [JSON]
:::
