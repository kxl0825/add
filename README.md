<b>Table 2. Semantic-targeted FGSM results (video-level AUC) on FF++, CDFv2, and DFDC for the original model and ADE variants.</b>

<table>
  <thead>
    <tr>
      <th rowspan="2" style="text-align: center; vertical-align: middle;">Methods</th>
      <th colspan="4" style="text-align: center;">FF++</th>
      <th colspan="4" style="text-align: center;">CDFv2</th>
      <th colspan="4" style="text-align: center;">DFDC</th>
    </tr>
    <tr>
      <th style="text-align: center;">Clean</th>
      <th style="text-align: center;">1/255</th>
      <th style="text-align: center;">2/255</th>
      <th style="text-align: center;">4/255</th>
      <th style="text-align: center;">Clean</th>
      <th style="text-align: center;">1/255</th>
      <th style="text-align: center;">2/255</th>
      <th style="text-align: center;">4/255</th>
      <th style="text-align: center;">Clean</th>
      <th style="text-align: center;">1/255</th>
      <th style="text-align: center;">2/255</th>
      <th style="text-align: center;">4/255</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center;">(A)</td>
      <td style="text-align: center;">0.972</td>
      <td style="text-align: center;">0.614</td>
      <td style="text-align: center;">0.508</td>
      <td style="text-align: center;">0.132</td>
      <td style="text-align: center;">0.927</td>
      <td style="text-align: center;">0.601</td>
      <td style="text-align: center;">0.596</td>
      <td style="text-align: center;">0.128</td>
      <td style="text-align: center;">0.856</td>
      <td style="text-align: center;">0.567</td>
      <td style="text-align: center;">0.382</td>
      <td style="text-align: center;">0.121</td>
    </tr>
    <tr>
      <td style="text-align: center;">(D)</td>
      <td style="text-align: center;">0.981</td>
      <td style="text-align: center;">0.782</td>
      <td style="text-align: center;">0.644</td>
      <td style="text-align: center;">0.411</td>
      <td style="text-align: center;">0.956</td>
      <td style="text-align: center;">0.731</td>
      <td style="text-align: center;">0.602</td>
      <td style="text-align: center;">0.381</td>
      <td style="text-align: center;">0.874</td>
      <td style="text-align: center;">0.655</td>
      <td style="text-align: center;">0.497</td>
      <td style="text-align: center;">0.301</td>
    </tr>
    <tr>
      <td style="text-align: center;">(E)</td>
      <td style="text-align: center;">0.984</td>
      <td style="text-align: center;">0.865</td>
      <td style="text-align: center;">0.756</td>
      <td style="text-align: center;">0.563</td>
      <td style="text-align: center;">0.961</td>
      <td style="text-align: center;">0.812</td>
      <td style="text-align: center;">0.701</td>
      <td style="text-align: center;">0.501</td>
      <td style="text-align: center;">0.878</td>
      <td style="text-align: center;">0.742</td>
      <td style="text-align: center;">0.603</td>
      <td style="text-align: center;">0.418</td>
    </tr>
    <tr>
      <td style="text-align: center;"><b>Ours</b></td>
      <td style="text-align: center;"><b>0.998</b></td>
      <td style="text-align: center;"><b>0.971</b></td>
      <td style="text-align: center;"><b>0.957</b></td>
      <td style="text-align: center;"><b>0.950</b></td>
      <td style="text-align: center;"><b>0.977</b></td>
      <td style="text-align: center;"><b>0.931</b></td>
      <td style="text-align: center;"><b>0.904</b></td>
      <td style="text-align: center;"><b>0.876</b></td>
      <td style="text-align: center;"><b>0.882</b></td>
      <td style="text-align: center;"><b>0.811</b></td>
      <td style="text-align: center;"><b>0.756</b></td>
      <td style="text-align: center;"><b>0.701</b></td>
    </tr>
  </tbody>
</table>




<b>Table 3. Ours Mean Video-Level Evidential Uncertainty (0-1) under semantic-targeted FGSM attacks.</b>

<table>
  <thead>
    <tr>
      <th rowspan="2" style="text-align: center; vertical-align: middle;">Methods</th>
      <th colspan="4" style="text-align: center;">FF++</th>
      <th colspan="4" style="text-align: center;">CDFv2</th>
      <th colspan="4" style="text-align: center;">DFDC</th>
    </tr>
    <tr>
      <th style="text-align: center;">Clean</th>
      <th style="text-align: center;">1/255</th>
      <th style="text-align: center;">2/255</th>
      <th style="text-align: center;">4/255</th>
      <th style="text-align: center;">Clean</th>
      <th style="text-align: center;">1/255</th>
      <th style="text-align: center;">2/255</th>
      <th style="text-align: center;">4/255</th>
      <th style="text-align: center;">Clean</th>
      <th style="text-align: center;">1/255</th>
      <th style="text-align: center;">2/255</th>
      <th style="text-align: center;">4/255</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center;"><b>Ours</b></td>
      <td style="text-align: center;">0.034</td>
      <td style="text-align: center;">0.051</td>
      <td style="text-align: center;">0.133</td>
      <td style="text-align: center;">0.201</td>
      <td style="text-align: center;">0.056</td>
      <td style="text-align: center;">0.159</td>
      <td style="text-align: center;">0.231</td>
      <td style="text-align: center;">0.378</td>
      <td style="text-align: center;">0.147</td>
      <td style="text-align: center;">0.211</td>
      <td style="text-align: center;">0.392</td>
      <td style="text-align: center;">0.423</td>
    </tr>
  </tbody>
</table>






<b>Table 7. Dependence diagnostics before and after purification.</b>

<table style="margin: auto; margin-top: 10px;">
  <thead>
    <tr>
      <th style="text-align: left;">Method</th>
      <th style="text-align: center;">Mean Abs. Full Corr. ↓</th>
      <th style="text-align: center;">Gaussian MI Proxy ↓</th>
      <th style="text-align: center;">HSIC ↓</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left;">Before purification (<i>f<sub>s</sub></i> vs <i>f<sub>r</sub></i>)</td>
      <td style="text-align: center;">0.956</td>
      <td style="text-align: center;">6.561</td>
      <td style="text-align: center;">0.765</td>
    </tr>
    <tr>
      <td style="text-align: left;">After purification (<i>f<sub>s</sub></i> vs <i>f<sub>a</sub></i>)</td>
      <td style="text-align: center;">0.051</td>
      <td style="text-align: center;">0.032</td>
      <td style="text-align: center;">0.019</td>
    </tr>
    <tr>
      <td style="text-align: left;">Opinion evidence before purification (<i>e<sub>s</sub></i> vs <i>e<sub>r</sub></i>)</td>
      <td style="text-align: center;">0.916</td>
      <td style="text-align: center;">5.063</td>
      <td style="text-align: center;">0.647</td>
    </tr>
    <tr>
      <td style="text-align: left;">Opinion evidence after purification (<i>e<sub>s</sub></i> vs <i>e<sub>a</sub></i>)</td>
      <td style="text-align: center;">0.051</td>
      <td style="text-align: center;">0.031</td>
      <td style="text-align: center;">0.018</td>
    </tr>
  </tbody>
</table>


<b>Table 6. Supplementary efficiency comparison under a unified local profiling protocol.</b>

<table style="margin: auto; margin-top: 10px;">
  <thead>
    <tr>
      <th style="text-align: left;">Method</th>
      <th style="text-align: center;">Trainable Param. (M)</th>
      <th style="text-align: center;">GFLOPs</th>
      <th style="text-align: center;">Inference Time / Frame (ms)</th>
      <th style="text-align: center;">FPS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left;">Effort</td>
      <td style="text-align: center;">0.199</td>
      <td style="text-align: center;">103.893</td>
      <td style="text-align: center;">22.709 ± 0.431</td>
      <td style="text-align: center;">44.04</td>
    </tr>
    <tr>
      <td style="text-align: left;">GenD</td>
      <td style="text-align: center;">0.104</td>
      <td style="text-align: center;">155.634</td>
      <td style="text-align: center;">17.983 ± 0.027</td>
      <td style="text-align: center;">55.61</td>
    </tr>
    <tr>
      <td style="text-align: left;">Ours</td>
      <td style="text-align: center;">0.868</td>
      <td style="text-align: center;">156.080</td>
      <td style="text-align: center;">21.112 ± 0.322</td>
      <td style="text-align: center;">47.37</td>
    </tr>
  </tbody>
</table>





