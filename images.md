<style>
  section{ clear: both;  margin-top:36px;}
</style>
# Image Compare Options

## Side by Side

.ve-image  wc:Vincent_van_Gogh_-_Self-Portrait_-_Google_Art_Project_(454045).jpg
.ve-image  wc:Vincent_van_Gogh_-_Self-Portrait_-_Google_Art_Project.jpg 

## Compare (default)

.ve-image  compare
    - wc:Vincent_van_Gogh_-_Self-Portrait_-_Google_Art_Project_(454045).jpg
    - wc:Vincent_van_Gogh_-_Self-Portrait_-_Google_Art_Project.jpg  pct:13,10,70,85

## Compare (curtain mode)

.ve-image compare mode=curtain
    - wc:Vincent_van_Gogh_-_Self-Portrait_-_Google_Art_Project_(454045).jpg
    - wc:Vincent_van_Gogh_-_Self-Portrait_-_Google_Art_Project.jpg 

## Compare (sync mode)

.ve-image compare mode=sync
    - wc:Vincent_van_Gogh_-_Self-Portrait_-_Google_Art_Project_(454045).jpg
    - wc:Vincent_van_Gogh_-_Self-Portrait_-_Google_Art_Project.jpg

Q5435849