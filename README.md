# cambridge_trees
addCircleMarkers(
    data = trees_in_parks,
    radius = 2,
    color = "darkgreen",
    stroke = FALSE,
    fillOpacity = 0.7,
    group = "Trees in Parks"
  ) %>%

  # Add trees outside parks
  addCircleMarkers(
    data = trees_outside_parks,
    radius = 2,
    color = "orange",
    stroke = FALSE,
    fillOpacity = 0.6,
    group = "Trees Outside Parks"
  ) %>%
