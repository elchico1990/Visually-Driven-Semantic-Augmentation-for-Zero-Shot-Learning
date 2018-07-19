# Visually-Driven-Semantic-Augmentation-for-Zero-Shot-Learning

We tackle the zero-shot learning (ZSL) classification problem and analyse one of its key ingredients, the semantic embedding. Despite their fundamental role, semantic embeddings are not learnt from the visual data to be classified, but, instead, they either come from manual annotation (attributes) or from a linguistic text corpus (distributed word embeddings, DWEs). 

Hence, there is no guarantee that visual and semantic information could fit well, and as to bridge this gap, we propose to augment the semantic information of attributes/DWEs with semantic representations directly extracted from visual data by means of soft labels. 

When combined in a novel ZSL paradigm based on latent attributes, our approach achieves favourable performances on three public benchmark datasets.

## Code sharing for reproducibility

<img src="https://vignette.wikia.nocookie.net/breakingbad/images/0/08/Work-in-progress-1024x603.png/revision/latest?cb=20170515215858" width=20% height=20%> ... code will be available soon

## Parameters configurations

We provide the parameters configuration that we used in our BMVC 2018 paper for the results therein published


<table class="tg">
  <tr>
    <th class="tg-c3ow" colspan="7"><span style="font-weight:bold">Binary attributes anotated by human</span></th>
  </tr>
  <tr>
    <td class="tg-c3ow"><span style="font-weight:bold">Dataset</span></td>
    <td class="tg-us36" colspan="2">Baseline+<span style="font-weight:bold">A</span></td>
    <td class="tg-yw4l" colspan="2">VdSA+<span style="font-weight:bold">A</span>+<span style="font-weight:bold">H</span></td>
    <td class="tg-yw4l" colspan="2">VdSA+<span style="font-weight:bold">A</span>+<span style="font-weight:bold">S</span></td>
  </tr>
  <tr>
    <td class="tg-baqh"></td>
    <td class="tg-yw4l">alpha</td>
    <td class="tg-yw4l">beta</td>
    <td class="tg-yw4l">alpha</td>
    <td class="tg-yw4l">beta</td>
    <td class="tg-yw4l">alpha</td>
    <td class="tg-yw4l">beta</td>
  </tr>
  <tr>
    <td class="tg-baqh"><span style="font-weight:bold">ap&amp;Y</span></td>
    <td class="tg-baqh">50</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">10</td>
    <td class="tg-baqh">1</td>
  </tr>
  <tr>
    <td class="tg-c3ow"><span style="font-weight:bold">AwA</span></td>
    <td class="tg-c3ow">80</td>
    <td class="tg-c3ow">10</td>
    <td class="tg-baqh">50</td>
    <td class="tg-c3ow">1</td>
    <td class="tg-baqh">100</td>
    <td class="tg-c3ow">1</td>
  </tr>
  <tr>
    <td class="tg-baqh"><span style="font-weight:bold">CUB-200</span></td>
    <td class="tg-baqh">100</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">100</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">10</td>
  </tr>
</table>

### Distributed word embeddings
<table style="width:100%">
  <tr>
    <th> </th>
    <th> </th> 
    <th> </th>
  </tr>
  <tr>
    <td> </td>
    <td> </td> 
    <td> </td>
  </tr>
  <tr>
    <td> </td>
    <td> </td> 
    <td> </td>
  </tr>
</table>

### Combination of the two
<table style="width:100%">
  <tr>
    <th> </th>
    <th> </th> 
    <th> </th>
  </tr>
  <tr>
    <td> </td>
    <td> </td> 
    <td> </td>
  </tr>
  <tr>
    <td> </td>
    <td> </td> 
    <td> </td>
  </tr>
</table>

If you use our code, please consider citing the following work

    @InProceedings{Roy-VdSA:BMVC18,
        title={Visually-Driven Semantic Augmentation for Zero-Shot Learning},
        author={Roy, Abhinaba and Cavazza, Jacopo and Murino, Vittorio},
        booktitle = {Proceedings of the 29th British Machine Vision Conference (BMVC)},
        year={2018}
    } 
