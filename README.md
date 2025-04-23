# cambridge_trees

# Add layer control for toggling
  addLayersControl(
    overlayGroups = c("Trees in Parks", 
"Trees Outside Parks", "Parks"),
    options = layersControlOptions(collapsed 
= FALSE)
  ) %>%

  # Add custom legend
  addLegend(
    position = "bottomright",
    colors = c("darkgreen", "orange", 
"lightblue"),
    labels = c("Trees in Parks", "Trees Outside 
Parks", "Parks"),
    title = "Layers"
  )
