building damage probability with consideration of burn.png: p(dm|bp)*p(bp)
building EAL: loss*area* p(dm|bp)*p(bp)
burn_probability_map.png: output of step 1, burn probability
distribution_burning_probability.png: distribution of burning probability for all buildings
Damaged probability.png: building damage probability once the land is in burned.  p(dm|bp)
Damaged building.png: damaged buildings  once the land is in burned.  

gdf_damage_prob_and_loss.geojson: geojson data include all the features, and outputs like damage probability, expected loss, etc.
damage_prob_expected_loss.tif： tif includes building damage probability and expected loss.
3d_surface_total_expected_loss.png: community-scale total EAL.

threshold_vs_damaged_buildings.png： predicted damaged building under different confidence thresholds