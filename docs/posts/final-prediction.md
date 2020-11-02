## The mobilization battle: turnout and vote share
### October 24, 2020

[Back to main page](https://hwsimpson33.github.io/pres2020/)

-Explain model basics
-Justification (cite king paper)
-Predictions + intervals
maps
predictions table

-dive into the model itself (formula, interpretation of coefficients)
coefficients table
-discuss model validation

<table style="border-collapse:collapse;" class=table_9844 border=2>
<thead>
<tr>
  <th id="tableHTML_header_1">State</th>
  <th id="tableHTML_header_2">Point prediction</th>
  <th id="tableHTML_header_3">Lower bound</th>
  <th id="tableHTML_header_4">Upper bound</th>
</tr>
</thead>
<tbody>
<tr>
  <td id="tableHTML_column_1">Alabama</td>
  <td id="tableHTML_column_2">21.9206</td>
  <td id="tableHTML_column_3">17.9306</td>
  <td id="tableHTML_column_4">25.9106</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Alaska</td>
  <td id="tableHTML_column_2">18.3274</td>
  <td id="tableHTML_column_3">11.742</td>
  <td id="tableHTML_column_4">24.9128</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Arizona</td>
  <td id="tableHTML_column_2">-2.0955</td>
  <td id="tableHTML_column_3">-7.4569</td>
  <td id="tableHTML_column_4">3.266</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Arkansas</td>
  <td id="tableHTML_column_2">36.8509</td>
  <td id="tableHTML_column_3">29.6191</td>
  <td id="tableHTML_column_4">44.0827</td>
</tr>
<tr>
  <td id="tableHTML_column_1">California</td>
  <td id="tableHTML_column_2">-32.6088</td>
  <td id="tableHTML_column_3">-38.0509</td>
  <td id="tableHTML_column_4">-27.1667</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Colorado</td>
  <td id="tableHTML_column_2">-12.3174</td>
  <td id="tableHTML_column_3">-17.4075</td>
  <td id="tableHTML_column_4">-7.2273</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Connecticut</td>
  <td id="tableHTML_column_2">-24.8847</td>
  <td id="tableHTML_column_3">-28.8681</td>
  <td id="tableHTML_column_4">-20.9013</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Delaware</td>
  <td id="tableHTML_column_2">-16.9962</td>
  <td id="tableHTML_column_3">-22.3808</td>
  <td id="tableHTML_column_4">-11.6117</td>
</tr>
<tr>
  <td id="tableHTML_column_1">District of Columbia</td>
  <td id="tableHTML_column_2">-91.3904</td>
  <td id="tableHTML_column_3">NA</td>
  <td id="tableHTML_column_4">NA</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Florida</td>
  <td id="tableHTML_column_2">-1.9009</td>
  <td id="tableHTML_column_3">-5.7258</td>
  <td id="tableHTML_column_4">1.924</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Georgia</td>
  <td id="tableHTML_column_2">-1.1112</td>
  <td id="tableHTML_column_3">-4.1402</td>
  <td id="tableHTML_column_4">1.9177</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Hawaii</td>
  <td id="tableHTML_column_2">-44.3101</td>
  <td id="tableHTML_column_3">-54.2868</td>
  <td id="tableHTML_column_4">-34.3334</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Idaho</td>
  <td id="tableHTML_column_2">31.7868</td>
  <td id="tableHTML_column_3">23.2333</td>
  <td id="tableHTML_column_4">40.3403</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Illinois</td>
  <td id="tableHTML_column_2">-16.0511</td>
  <td id="tableHTML_column_3">-20.9296</td>
  <td id="tableHTML_column_4">-11.1727</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Indiana</td>
  <td id="tableHTML_column_2">12.4095</td>
  <td id="tableHTML_column_3">7.7011</td>
  <td id="tableHTML_column_4">17.1178</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Iowa</td>
  <td id="tableHTML_column_2">2.662</td>
  <td id="tableHTML_column_3">-2.1048</td>
  <td id="tableHTML_column_4">7.4287</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Kansas</td>
  <td id="tableHTML_column_2">15.5149</td>
  <td id="tableHTML_column_3">12.4522</td>
  <td id="tableHTML_column_4">18.5777</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Kentucky</td>
  <td id="tableHTML_column_2">26.2653</td>
  <td id="tableHTML_column_3">17.0039</td>
  <td id="tableHTML_column_4">35.5267</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Louisiana</td>
  <td id="tableHTML_column_2">27.8796</td>
  <td id="tableHTML_column_3">19.6197</td>
  <td id="tableHTML_column_4">36.1394</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Maine</td>
  <td id="tableHTML_column_2">-17.6871</td>
  <td id="tableHTML_column_3">-29.087</td>
  <td id="tableHTML_column_4">-6.2872</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Maryland</td>
  <td id="tableHTML_column_2">-27.0475</td>
  <td id="tableHTML_column_3">-33.4209</td>
  <td id="tableHTML_column_4">-20.6741</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Massachusetts</td>
  <td id="tableHTML_column_2">-36.7493</td>
  <td id="tableHTML_column_3">-45.6899</td>
  <td id="tableHTML_column_4">-27.8086</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Michigan</td>
  <td id="tableHTML_column_2">-8.21</td>
  <td id="tableHTML_column_3">-11.7378</td>
  <td id="tableHTML_column_4">-4.6822</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Minnesota</td>
  <td id="tableHTML_column_2">-9.0042</td>
  <td id="tableHTML_column_3">-13.9381</td>
  <td id="tableHTML_column_4">-4.0703</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Mississippi</td>
  <td id="tableHTML_column_2">15.8242</td>
  <td id="tableHTML_column_3">9.5142</td>
  <td id="tableHTML_column_4">22.1342</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Missouri</td>
  <td id="tableHTML_column_2">5.0454</td>
  <td id="tableHTML_column_3">-1.5984</td>
  <td id="tableHTML_column_4">11.6892</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Montana</td>
  <td id="tableHTML_column_2">2.8581</td>
  <td id="tableHTML_column_3">-1.2768</td>
  <td id="tableHTML_column_4">6.9929</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Nebraska</td>
  <td id="tableHTML_column_2">9.642</td>
  <td id="tableHTML_column_3">-1.8754</td>
  <td id="tableHTML_column_4">21.1594</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Nevada</td>
  <td id="tableHTML_column_2">-11.6623</td>
  <td id="tableHTML_column_3">-19.2428</td>
  <td id="tableHTML_column_4">-4.0817</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New Hampshire</td>
  <td id="tableHTML_column_2">-8.087</td>
  <td id="tableHTML_column_3">-20.756</td>
  <td id="tableHTML_column_4">4.582</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New Jersey</td>
  <td id="tableHTML_column_2">-24.1546</td>
  <td id="tableHTML_column_3">-30.5625</td>
  <td id="tableHTML_column_4">-17.7468</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New Mexico</td>
  <td id="tableHTML_column_2">-13.5394</td>
  <td id="tableHTML_column_3">-18.3251</td>
  <td id="tableHTML_column_4">-8.7537</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New York</td>
  <td id="tableHTML_column_2">-31.9772</td>
  <td id="tableHTML_column_3">-34.7415</td>
  <td id="tableHTML_column_4">-29.213</td>
</tr>
<tr>
  <td id="tableHTML_column_1">North Carolina</td>
  <td id="tableHTML_column_2">1.2296</td>
  <td id="tableHTML_column_3">-3.286</td>
  <td id="tableHTML_column_4">5.7453</td>
</tr>
<tr>
  <td id="tableHTML_column_1">North Dakota</td>
  <td id="tableHTML_column_2">22.49</td>
  <td id="tableHTML_column_3">8.8546</td>
  <td id="tableHTML_column_4">36.1254</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Ohio</td>
  <td id="tableHTML_column_2">4.2218</td>
  <td id="tableHTML_column_3">1.8641</td>
  <td id="tableHTML_column_4">6.5795</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Oklahoma</td>
  <td id="tableHTML_column_2">25.4681</td>
  <td id="tableHTML_column_3">18.3076</td>
  <td id="tableHTML_column_4">32.6286</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Oregon</td>
  <td id="tableHTML_column_2">-16.6433</td>
  <td id="tableHTML_column_3">-20.3242</td>
  <td id="tableHTML_column_4">-12.9624</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Pennsylvania</td>
  <td id="tableHTML_column_2">-6.7752</td>
  <td id="tableHTML_column_3">-10.1509</td>
  <td id="tableHTML_column_4">-3.3996</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Rhode Island</td>
  <td id="tableHTML_column_2">-16.6214</td>
  <td id="tableHTML_column_3">NA</td>
  <td id="tableHTML_column_4">NA</td>
</tr>
<tr>
  <td id="tableHTML_column_1">South Carolina</td>
  <td id="tableHTML_column_2">9.8522</td>
  <td id="tableHTML_column_3">5.3622</td>
  <td id="tableHTML_column_4">14.3422</td>
</tr>
<tr>
  <td id="tableHTML_column_1">South Dakota</td>
  <td id="tableHTML_column_2">15.0019</td>
  <td id="tableHTML_column_3">4.3802</td>
  <td id="tableHTML_column_4">25.6235</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Tennessee</td>
  <td id="tableHTML_column_2">22.0115</td>
  <td id="tableHTML_column_3">13.0487</td>
  <td id="tableHTML_column_4">30.9744</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Texas</td>
  <td id="tableHTML_column_2">6.0978</td>
  <td id="tableHTML_column_3">1.7412</td>
  <td id="tableHTML_column_4">10.4544</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Utah</td>
  <td id="tableHTML_column_2">23.1254</td>
  <td id="tableHTML_column_3">17.4026</td>
  <td id="tableHTML_column_4">28.8481</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Vermont</td>
  <td id="tableHTML_column_2">-31.0238</td>
  <td id="tableHTML_column_3">-37.1263</td>
  <td id="tableHTML_column_4">-24.9213</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Virginia</td>
  <td id="tableHTML_column_2">-10.9369</td>
  <td id="tableHTML_column_3">-16.8387</td>
  <td id="tableHTML_column_4">-5.0351</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Washington</td>
  <td id="tableHTML_column_2">-25.0204</td>
  <td id="tableHTML_column_3">-29.4365</td>
  <td id="tableHTML_column_4">-20.6042</td>
</tr>
<tr>
  <td id="tableHTML_column_1">West Virginia</td>
  <td id="tableHTML_column_2">42.0839</td>
  <td id="tableHTML_column_3">33.5751</td>
  <td id="tableHTML_column_4">50.5926</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Wisconsin</td>
  <td id="tableHTML_column_2">-7.8144</td>
  <td id="tableHTML_column_3">-12.1085</td>
  <td id="tableHTML_column_4">-3.5203</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Wyoming</td>
  <td id="tableHTML_column_2">51.4106</td>
  <td id="tableHTML_column_3">NA</td>
  <td id="tableHTML_column_4">NA</td>
</tr>
</tbody>
</table>


<tr>
  <td id="tableHTML_column_1">Florida</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.3301</td>
  <td id="tableHTML_column_4">0.1782</td>
  <td id="tableHTML_column_5">1e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Florida</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.2142</td>
  <td id="tableHTML_column_4">0.1408</td>
  <td id="tableHTML_column_5">0.172</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Georgia</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">0.6051</td>
  <td id="tableHTML_column_4">1.3717</td>
  <td id="tableHTML_column_5">0.6724</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Georgia</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.1619</td>
  <td id="tableHTML_column_4">0.0968</td>
  <td id="tableHTML_column_5">0</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Georgia</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.0102</td>
  <td id="tableHTML_column_4">0.0616</td>
  <td id="tableHTML_column_5">0.8726</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Hawaii</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">3.8651</td>
  <td id="tableHTML_column_4">4.8515</td>
  <td id="tableHTML_column_5">0.456</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Hawaii</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.5246</td>
  <td id="tableHTML_column_4">0.3087</td>
  <td id="tableHTML_column_5">0.0026</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Hawaii</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.0699</td>
  <td id="tableHTML_column_4">0.1518</td>
  <td id="tableHTML_column_5">0.6614</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Idaho</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">19.8745</td>
  <td id="tableHTML_column_4">12.9425</td>
  <td id="tableHTML_column_5">0.1755</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Idaho</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.6523</td>
  <td id="tableHTML_column_4">0.3199</td>
  <td id="tableHTML_column_5">0.0876</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Idaho</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.1232</td>
  <td id="tableHTML_column_4">0.3311</td>
  <td id="tableHTML_column_5">0.7226</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Illinois</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-1.5205</td>
  <td id="tableHTML_column_4">1.6357</td>
  <td id="tableHTML_column_5">0.3768</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Illinois</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.748</td>
  <td id="tableHTML_column_4">0.1296</td>
  <td id="tableHTML_column_5">3e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Illinois</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.2623</td>
  <td id="tableHTML_column_4">0.1365</td>
  <td id="tableHTML_column_5">0.0869</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Indiana</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">0.5944</td>
  <td id="tableHTML_column_4">5.254</td>
  <td id="tableHTML_column_5">0.9131</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Indiana</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.9446</td>
  <td id="tableHTML_column_4">0.2751</td>
  <td id="tableHTML_column_5">0.0109</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Indiana</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.2571</td>
  <td id="tableHTML_column_4">0.2102</td>
  <td id="tableHTML_column_5">0.2609</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Iowa</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">1.1237</td>
  <td id="tableHTML_column_4">1.4279</td>
  <td id="tableHTML_column_5">0.454</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Iowa</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.8076</td>
  <td id="tableHTML_column_4">0.1551</td>
  <td id="tableHTML_column_5">8e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Iowa</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.1474</td>
  <td id="tableHTML_column_4">0.1454</td>
  <td id="tableHTML_column_5">0.3404</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Kansas</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">10.7463</td>
  <td id="tableHTML_column_4">3.4901</td>
  <td id="tableHTML_column_5">0.0132</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Kansas</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.7431</td>
  <td id="tableHTML_column_4">0.0996</td>
  <td id="tableHTML_column_5">0</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Kansas</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.1031</td>
  <td id="tableHTML_column_4">0.1222</td>
  <td id="tableHTML_column_5">0.421</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Kentucky</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">2.7335</td>
  <td id="tableHTML_column_4">2.9749</td>
  <td id="tableHTML_column_5">0.3887</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Kentucky</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.9793</td>
  <td id="tableHTML_column_4">0.1706</td>
  <td id="tableHTML_column_5">7e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Kentucky</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.2196</td>
  <td id="tableHTML_column_4">0.1801</td>
  <td id="tableHTML_column_5">0.2621</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Louisiana</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-1.5876</td>
  <td id="tableHTML_column_4">2.2113</td>
  <td id="tableHTML_column_5">0.4998</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Louisiana</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.1365</td>
  <td id="tableHTML_column_4">0.2138</td>
  <td id="tableHTML_column_5">0.0018</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Louisiana</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.1691</td>
  <td id="tableHTML_column_4">0.1419</td>
  <td id="tableHTML_column_5">0.2783</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Maine</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">2.9667</td>
  <td id="tableHTML_column_4">4.4593</td>
  <td id="tableHTML_column_5">0.5272</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Maine</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.5711</td>
  <td id="tableHTML_column_4">0.6371</td>
  <td id="tableHTML_column_5">0.0431</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Maine</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.0717</td>
  <td id="tableHTML_column_4">0.1921</td>
  <td id="tableHTML_column_5">0.7201</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Maryland</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-3.9466</td>
  <td id="tableHTML_column_4">2.1122</td>
  <td id="tableHTML_column_5">0.0986</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Maryland</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.7637</td>
  <td id="tableHTML_column_4">0.1681</td>
  <td id="tableHTML_column_5">0.0019</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Maryland</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.1402</td>
  <td id="tableHTML_column_4">0.1351</td>
  <td id="tableHTML_column_5">0.3296</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Massachusetts</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-7.0869</td>
  <td id="tableHTML_column_4">3.6383</td>
  <td id="tableHTML_column_5">0.0833</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Massachusetts</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.7742</td>
  <td id="tableHTML_column_4">0.1936</td>
  <td id="tableHTML_column_5">0.0031</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Massachusetts</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.0876</td>
  <td id="tableHTML_column_4">0.2014</td>
  <td id="tableHTML_column_5">0.674</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Michigan</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-0.2648</td>
  <td id="tableHTML_column_4">1.1931</td>
  <td id="tableHTML_column_5">0.8299</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Michigan</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.929</td>
  <td id="tableHTML_column_4">0.1331</td>
  <td id="tableHTML_column_5">1e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Michigan</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.188</td>
  <td id="tableHTML_column_4">0.1056</td>
  <td id="tableHTML_column_5">0.1129</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Minnesota</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-5.4034</td>
  <td id="tableHTML_column_4">2.6049</td>
  <td id="tableHTML_column_5">0.0679</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Minnesota</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.422</td>
  <td id="tableHTML_column_4">0.152</td>
  <td id="tableHTML_column_5">0.0215</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Minnesota</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.0339</td>
  <td id="tableHTML_column_4">0.2453</td>
  <td id="tableHTML_column_5">0.8933</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Mississippi</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">1.6051</td>
  <td id="tableHTML_column_4">5.9381</td>
  <td id="tableHTML_column_5">0.7977</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Mississippi</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.4269</td>
  <td id="tableHTML_column_4">0.3502</td>
  <td id="tableHTML_column_5">0.2773</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Mississippi</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.4534</td>
  <td id="tableHTML_column_4">0.2549</td>
  <td id="tableHTML_column_5">0.1354</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Missouri</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">2.1055</td>
  <td id="tableHTML_column_4">1.8817</td>
  <td id="tableHTML_column_5">0.2922</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Missouri</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.702</td>
  <td id="tableHTML_column_4">0.1173</td>
  <td id="tableHTML_column_5">2e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Missouri</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.0233</td>
  <td id="tableHTML_column_4">0.1608</td>
  <td id="tableHTML_column_5">0.8879</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Montana</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">2.4739</td>
  <td id="tableHTML_column_4">1.5894</td>
  <td id="tableHTML_column_5">0.1803</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Montana</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.3081</td>
  <td id="tableHTML_column_4">0.1209</td>
  <td id="tableHTML_column_5">1e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Montana</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.3679</td>
  <td id="tableHTML_column_4">0.0993</td>
  <td id="tableHTML_column_5">0.0139</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Nebraska</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">11.6138</td>
  <td id="tableHTML_column_4">7.0689</td>
  <td id="tableHTML_column_5">0.139</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Nebraska</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.7904</td>
  <td id="tableHTML_column_4">0.2082</td>
  <td id="tableHTML_column_5">0.0053</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Nebraska</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.0031</td>
  <td id="tableHTML_column_4">0.1922</td>
  <td id="tableHTML_column_5">0.9877</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Nevada</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-2.1365</td>
  <td id="tableHTML_column_4">2.2982</td>
  <td id="tableHTML_column_5">0.3884</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Nevada</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.6682</td>
  <td id="tableHTML_column_4">0.2599</td>
  <td id="tableHTML_column_5">7e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Nevada</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.0257</td>
  <td id="tableHTML_column_4">0.1647</td>
  <td id="tableHTML_column_5">0.8813</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New Hampshire</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">2.8986</td>
  <td id="tableHTML_column_4">3.8964</td>
  <td id="tableHTML_column_5">0.4811</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New Hampshire</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.9175</td>
  <td id="tableHTML_column_4">0.3786</td>
  <td id="tableHTML_column_5">0.0459</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New Hampshire</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.3119</td>
  <td id="tableHTML_column_4">0.2583</td>
  <td id="tableHTML_column_5">0.2665</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New Jersey</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-0.6769</td>
  <td id="tableHTML_column_4">1.5631</td>
  <td id="tableHTML_column_5">0.6752</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New Jersey</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.9767</td>
  <td id="tableHTML_column_4">0.1374</td>
  <td id="tableHTML_column_5">1e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New Jersey</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.1255</td>
  <td id="tableHTML_column_4">0.1274</td>
  <td id="tableHTML_column_5">0.3505</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New Mexico</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-1.4029</td>
  <td id="tableHTML_column_4">1.3829</td>
  <td id="tableHTML_column_5">0.3495</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New Mexico</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.0109</td>
  <td id="tableHTML_column_4">0.2004</td>
  <td id="tableHTML_column_5">0.0023</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New Mexico</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.1081</td>
  <td id="tableHTML_column_4">0.1755</td>
  <td id="tableHTML_column_5">0.5606</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New York</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-3.0765</td>
  <td id="tableHTML_column_4">1.1564</td>
  <td id="tableHTML_column_5">0.026</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New York</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.9562</td>
  <td id="tableHTML_column_4">0.0695</td>
  <td id="tableHTML_column_5">0</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">New York</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.1526</td>
  <td id="tableHTML_column_4">0.0654</td>
  <td id="tableHTML_column_5">0.0446</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">North Carolina</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">4.6305</td>
  <td id="tableHTML_column_4">2.0403</td>
  <td id="tableHTML_column_5">0.0494</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">North Carolina</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.9015</td>
  <td id="tableHTML_column_4">0.1123</td>
  <td id="tableHTML_column_5">0</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">North Carolina</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.188</td>
  <td id="tableHTML_column_4">0.1159</td>
  <td id="tableHTML_column_5">0.1393</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">North Dakota</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">12.3213</td>
  <td id="tableHTML_column_4">5.8634</td>
  <td id="tableHTML_column_5">0.0803</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">North Dakota</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.1837</td>
  <td id="tableHTML_column_4">0.2411</td>
  <td id="tableHTML_column_5">0.0027</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">North Dakota</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.3615</td>
  <td id="tableHTML_column_4">0.2194</td>
  <td id="tableHTML_column_5">0.1506</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Ohio</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">1.7084</td>
  <td id="tableHTML_column_4">1.0928</td>
  <td id="tableHTML_column_5">0.1524</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Ohio</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.8349</td>
  <td id="tableHTML_column_4">0.0931</td>
  <td id="tableHTML_column_5">0</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Ohio</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.2293</td>
  <td id="tableHTML_column_4">0.1052</td>
  <td id="tableHTML_column_5">0.0573</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Oklahoma</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">8.8833</td>
  <td id="tableHTML_column_4">3.8334</td>
  <td id="tableHTML_column_5">0.0536</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Oklahoma</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.8824</td>
  <td id="tableHTML_column_4">0.1283</td>
  <td id="tableHTML_column_5">2e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Oklahoma</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.0733</td>
  <td id="tableHTML_column_4">0.1483</td>
  <td id="tableHTML_column_5">0.6365</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Oregon</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-0.5472</td>
  <td id="tableHTML_column_4">0.9689</td>
  <td id="tableHTML_column_5">0.586</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Oregon</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.039</td>
  <td id="tableHTML_column_4">0.1351</td>
  <td id="tableHTML_column_5">0</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Oregon</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.0838</td>
  <td id="tableHTML_column_4">0.1187</td>
  <td id="tableHTML_column_5">0.4983</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Pennsylvania</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-0.8794</td>
  <td id="tableHTML_column_4">1.1016</td>
  <td id="tableHTML_column_5">0.4478</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Pennsylvania</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.0188</td>
  <td id="tableHTML_column_4">0.1194</td>
  <td id="tableHTML_column_5">0</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Pennsylvania</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.2585</td>
  <td id="tableHTML_column_4">0.1743</td>
  <td id="tableHTML_column_5">0.1763</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Rhode Island</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">0.3846</td>
  <td id="tableHTML_column_4">2.5853</td>
  <td id="tableHTML_column_5">0.8859</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Rhode Island</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.9127</td>
  <td id="tableHTML_column_4">0.1148</td>
  <td id="tableHTML_column_5">1e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Rhode Island</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.3076</td>
  <td id="tableHTML_column_4">0.1009</td>
  <td id="tableHTML_column_5">0.0186</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">South Carolina</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">3.5457</td>
  <td id="tableHTML_column_4">3.2398</td>
  <td id="tableHTML_column_5">0.31</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">South Carolina</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.0306</td>
  <td id="tableHTML_column_4">0.2387</td>
  <td id="tableHTML_column_5">0.0035</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">South Carolina</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.0842</td>
  <td id="tableHTML_column_4">0.1308</td>
  <td id="tableHTML_column_5">0.5402</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">South Dakota</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">3.0049</td>
  <td id="tableHTML_column_4">4.0022</td>
  <td id="tableHTML_column_5">0.4772</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">South Dakota</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.3152</td>
  <td id="tableHTML_column_4">0.2438</td>
  <td id="tableHTML_column_5">0.001</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">South Dakota</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.0773</td>
  <td id="tableHTML_column_4">0.2091</td>
  <td id="tableHTML_column_5">0.7223</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Tennessee</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">5.3139</td>
  <td id="tableHTML_column_4">2.1567</td>
  <td id="tableHTML_column_5">0.0489</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Tennessee</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.9225</td>
  <td id="tableHTML_column_4">0.2362</td>
  <td id="tableHTML_column_5">0.0079</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Tennessee</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.1185</td>
  <td id="tableHTML_column_4">0.2006</td>
  <td id="tableHTML_column_5">0.5762</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Texas</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">6.1999</td>
  <td id="tableHTML_column_4">2.3622</td>
  <td id="tableHTML_column_5">0.0342</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Texas</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.6573</td>
  <td id="tableHTML_column_4">0.1101</td>
  <td id="tableHTML_column_5">6e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Texas</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.03</td>
  <td id="tableHTML_column_4">0.1244</td>
  <td id="tableHTML_column_5">0.8163</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Utah</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">17.9446</td>
  <td id="tableHTML_column_4">4.7621</td>
  <td id="tableHTML_column_5">0.007</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Utah</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.6953</td>
  <td id="tableHTML_column_4">0.0786</td>
  <td id="tableHTML_column_5">0</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Utah</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.0575</td>
  <td id="tableHTML_column_4">0.1036</td>
  <td id="tableHTML_column_5">0.596</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Vermont</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-0.8859</td>
  <td id="tableHTML_column_4">3.9954</td>
  <td id="tableHTML_column_5">0.8333</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Vermont</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.4723</td>
  <td id="tableHTML_column_4">0.3543</td>
  <td id="tableHTML_column_5">0.0089</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Vermont</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.1358</td>
  <td id="tableHTML_column_4">0.1904</td>
  <td id="tableHTML_column_5">0.5078</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Virginia</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">0.2124</td>
  <td id="tableHTML_column_4">1.5382</td>
  <td id="tableHTML_column_5">0.8941</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Virginia</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.9019</td>
  <td id="tableHTML_column_4">0.1402</td>
  <td id="tableHTML_column_5">4e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Virginia</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.1641</td>
  <td id="tableHTML_column_4">0.1436</td>
  <td id="tableHTML_column_5">0.2906</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Washington</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">0.1568</td>
  <td id="tableHTML_column_4">1.1193</td>
  <td id="tableHTML_column_5">0.8921</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Washington</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.0461</td>
  <td id="tableHTML_column_4">0.1404</td>
  <td id="tableHTML_column_5">1e-04</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Washington</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.1231</td>
  <td id="tableHTML_column_4">0.1046</td>
  <td id="tableHTML_column_5">0.273</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">West Virginia</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">4.6559</td>
  <td id="tableHTML_column_4">1.1365</td>
  <td id="tableHTML_column_5">0.0046</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">West Virginia</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.1338</td>
  <td id="tableHTML_column_4">0.1109</td>
  <td id="tableHTML_column_5">0</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">West Virginia</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">0.2049</td>
  <td id="tableHTML_column_4">0.1065</td>
  <td id="tableHTML_column_5">0.0958</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Wisconsin</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">-0.9881</td>
  <td id="tableHTML_column_4">1.3115</td>
  <td id="tableHTML_column_5">0.4758</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Wisconsin</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">0.8323</td>
  <td id="tableHTML_column_4">0.1676</td>
  <td id="tableHTML_column_5">0.0016</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Wisconsin</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.0942</td>
  <td id="tableHTML_column_4">0.1875</td>
  <td id="tableHTML_column_5">0.6308</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Wyoming</td>
  <td id="tableHTML_column_2">(Intercept)</td>
  <td id="tableHTML_column_3">8.074</td>
  <td id="tableHTML_column_4">7.0066</td>
  <td id="tableHTML_column_5">0.3327</td>
  <td id="tableHTML_column_6">Intercept</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Wyoming</td>
  <td id="tableHTML_column_2">rlead.030</td>
  <td id="tableHTML_column_3">1.425</td>
  <td id="tableHTML_column_4">0.3294</td>
  <td id="tableHTML_column_5">0.0228</td>
  <td id="tableHTML_column_6">Republican lead in last 30 days</td>
</tr>
<tr>
  <td id="tableHTML_column_1">Wyoming</td>
  <td id="tableHTML_column_2">rlead.prev</td>
  <td id="tableHTML_column_3">-0.3785</td>
  <td id="tableHTML_column_4">0.2819</td>
  <td id="tableHTML_column_5">0.272</td>
  <td id="tableHTML_column_6">Republican win/loss margin in previous election</td>
</tr>
</tbody>
</table>



[Back to main page](https://hwsimpson33.github.io/pres2020/)