<h1>Dataset Description: <code>deadorgone</code> and <code>alldata_full</code></h1>

<p>
This README explains the structure and meaning of the datasets 
<strong><code>deadorgone</code></strong> and <strong><code>alldata_full</code></strong>.
Most columns are identical between datasets.
</p>

<h2>Column Descriptions</h2>

<h3>Species</h3>
<p>
The 4-letter taxonomic code describing the identity of each coral species.
Where identification was not possible, species were grouped into morphotaxa:
</p>

<table>
<thead>
<tr><th>Code</th><th>Description</th></tr>
</thead>
<tbody>
<tr><td><strong>Atab</strong></td><td>Tabular Acropora</td></tr>
<tr><td><strong>Poci</strong></td><td>Branching Pocillopora (damicornis &amp; verrucosa)</td></tr>
<tr><td><strong>Adgt</strong></td><td>Acropora digitate</td></tr>
<tr><td><strong>Spis</strong></td><td>Stylophora pistillata</td></tr>
<tr><td><strong>Pmas</strong></td><td>Porites massive</td></tr>
<tr><td><strong>Gspp</strong></td><td>Goniastrea spp (submassive)</td></tr>
<tr><td><strong>Plat</strong></td><td>Platygyra spp (submassive)</td></tr>
<tr><td><strong>Acor</strong></td><td>Corymbose Acropora</td></tr>
</tbody>
</table>

<h3>Environmental &amp; Colony Metrics</h3>
<ul>
<li><strong>temp_mean</strong> – Average daily temperature (°C) derived from eReefs.</li>
<li><strong>ubedmean</strong> – Near-bed water velocity (m/s) from the Callaghan wave model.</li>
<li><strong>Turbidity_mean</strong> – NTU, daily averages from 1 Jan 2015 – 1 Jan 2021.</li>
<li><strong>rugosity</strong> – Plot-level rugosity from 3D models relative to a plane of best fit.</li>
<li><strong>Depth</strong> – Shallow (3–5 m) or Deep (13–15 m).</li>
<li><strong>Plot_ID</strong> – Unique ID for each 12×6 m plot.</li>
<li><strong>Area_2022</strong> – Colony planar area in 2022 (cm²).</li>
<li><strong>Area_2021</strong> – Colony planar area in 2021 (cm²).</li>
<li><strong>return_months</strong> – Return time (nearest month).</li>
<li><strong>shelf_position</strong> – Inshore, offshore, or Torres Strait.</li>
<li><strong>habitat</strong> – Front (exposed), Back (sheltered), Flank (moderately exposed).</li>
<li><strong>region</strong> – Central, Northern, Southern, or Torres Strait.</li>
<li><strong>reef</strong> – Reef name.</li>
<li><strong>FD_Rugosity_Plane</strong> – Fractal dimension of rugosity adjusted to plane.</li>
<li><strong>PAR_mean</strong> – Average PAR (mol photon m⁻² s⁻¹), 2015–2021.</li>
<li><strong>site</strong> – Unique plot code.</li>
<li><strong>hard_coral_21</strong> – Hard coral cover in 2021.</li>
</ul>

<h3>Growth Metrics (not used in analyses)</h3>
<ul>
<li><strong>mothlygrowth</strong> – Monthly 2D growth (cm²).</li>
<li><strong>yearlygrowth</strong> – Annualised 2D growth (cm²).</li>
</ul>

<h3>Adjusted &amp; Transformed Area Metrics</h3>
<ul>
<li><strong>area_2022_adjusted</strong> – Area adjusted for variation in return time.</li>
<li><strong>log22</strong> – ln(area in year 2).</li>
<li><strong>log21</strong> – ln(area in year 1).</li>
<li><strong>log22_adj</strong> – ln(adjusted area in year 2).</li>
</ul>

<h2>EcoRRAP Abbreviations</h2>

<h3>Clusters</h3>
<ul>
<li><strong>CB</strong> – Capricorn Bunkers</li>
<li><strong>KE</strong> – Keppel Islands</li>
<li><strong>OC</strong> – Offshore Central</li>
<li><strong>PA</strong> – Palm Islands</li>
<li><strong>ON</strong> – Offshore Northern</li>
<li><strong>TS</strong> – Torres Strait</li>
</ul>

<h3>Reefs</h3>
<ul>
<li><strong>LM</strong> – Lady Musgrave</li>
<li><strong>HE</strong> – Heron Island</li>
<li><strong>HW</strong> – Halfway Island (Keppel)</li>
<li><strong>GK</strong> – Great Keppel Island</li>
<li><strong>MD</strong> – Middle Island (Keppel)</li>
<li><strong>ML</strong> – Miall Island (Keppel)</li>
<li><strong>NK</strong> – North Keppel Island</li>
<li><strong>DA</strong> – Davies Reef</li>
<li><strong>LB</strong> – Little Broadhurst Reef</li>
<li><strong>CH</strong> – Chicken Reef</li>
<li><strong>OR</strong> – Orpheus Island</li>
<li><strong>PE</strong> – Pelorus Island</li>
<li><strong>MO</strong> – Moore Reef</li>
<li><strong>LI</strong> – Lizard Island</li>
<li><strong>AU</strong> – Aukane Island</li>
<li><strong>DU</strong> – Dungeness Reef</li>
<li><strong>MA</strong> – Masig Island</li>
</ul>

<h3>Habitats</h3>
<p>(Numbers indicate multiple sites at the same reef: e.g., BA1 = Back 1)</p>
<ul>
<li><strong>BA</strong> – Back</li>
<li><strong>FL</strong> – Flank</li>
<li><strong>FR</strong> – Front</li>
<li><strong>LA</strong> – Lagoon</li>
</ul>

<h3>Example Code</h3>
<p>
A code such as <code>CBLM_FR1</code> breaks down as:
</p>
<ul>
<li><strong>CB</strong> – Capricorn Bunkers</li>
<li><strong>LM</strong> – Lady Musgrave</li>
<li><strong>FR</strong> – Front</li>
<li><strong>1</strong> – Plot number 1</li>
</ul>
