# Amazon Wild Roads Dataset

This repository contains the Amazon Wild Roads dataset. A diverse dataset that contains Sentinel 2 satellite images obtained from Google Earth Engine throughout 2020. Our dataset contains areas of Legal Amazonia where roads were mapped so that you can work with extracting roads from satellite images. Road annotations were carried out manually by specialists. 

The table below presents some information from the dataset. For more details you can access the article "Paving the Way for Automatic Mapping of Rural Roads in the Amazon Rainforest". You can find the code for our road extraction method by accessing this [link](https://github.com/lucascsfaria/ContextualPixelLevelRoadExtractionAmazon.git).

<table class="tg">
<thead>
<tr>
    <th colspan="2"><center>Amazon Wild Roads Dataset</center></th>
  </tr>
</thead>

<tbody>
  <tr>
    <td class="tg-0pky">Acquired areas</th>
    <td class="tg-0pky">28 satellite images</th>
  </tr>
  <tr>
    <td class="tg-0pky">Satellite</td>
    <td class="tg-0pky">Sentinel 2</td>
  </tr>
  <tr>
    <td class="tg-0pky">Image acquisition period</td>
    <td class="tg-0pky">All through 2020</td>
  </tr>
  <tr>
    <td class="tg-0pky">Extension of each area</td>
    <td class="tg-0pky">≅ 290 km²</td>
  </tr>
  <tr>
    <td class="tg-0pky">Total territorial extension</td>
    <td class="tg-0pky">≅ 8.120 km²</td>
  </tr>
  <tr>
    <td class="tg-0pky">Road annotations</td>
    <td class="tg-0pky">Manually annotated by specialists</td>
  </tr>
</tbody>
</table>


To view the acquired areas in our dataset, you can go [here](https://app.wildpixels.dcc.ufmg.br/). 

## How the dataset is organized

In total, we have five folders that contain files from each region. Below are descriptions of the folder contents:

`areas` &rarr; Folder with geojson files that contain the coordinates of areas in a polygon
`geojson_line`  &rarr; Folder with geojson files that contain manual annotations of roads in the areas
`image_geotif` &rarr; Folder with Satellite Sentinel 2 geotiff files obtained from Google Earth Engine for each area
`image_png` &rarr; Folder with files in PNG format of images converted from the `image_geotif` folder
`image_png` &rarr; Folder with masks in PNG format of the annotations contained in the `geojson_line` folder

## Citation for our paper

If you find Amazon Wild Roads (AWR) Dataset useful in your work, please consider citing the following BibTeX entry:

```bibtex
@inproceedings{faria2023paving,
  title={Paving the Way for Automatic Mapping of Rural Roads in the Amazon Rainforest},
  author={de Faria, Lucas Costa and Brito, Matheus and Nogueira, Keiller and dos Santos, Jefersson A.},
  booktitle={2023 36th SIBGRAPI Conference on Graphics, Patterns and Images (SIBGRAPI)},
  year={2023},
  organization={IEEE}
}
```