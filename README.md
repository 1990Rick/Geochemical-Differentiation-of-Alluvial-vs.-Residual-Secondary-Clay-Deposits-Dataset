1. Introduction and Dataset Overview
This document provides an exhaustive, column-by-column reference guide for the comprehensive research dataset entitled “Geochemical Differentiation of Alluvial vs. Residual Secondary Clay Deposits Exploited by Neolithic Potters in the Southern Levant: Implications for Localized Resource Territories and Community-Level Craft Organization.” The dataset comprises 18 individual worksheets, each containing precisely 5,000 data records with 17–23 columns, yielding a total of 90,000 records across approximately 360 distinct data fields.
The dataset integrates geochemical, mineralogical, petrographic, physical, statistical, spatial, and socio-economic parameters that collectively characterise the clay resource landscape of the Southern Levant during the Neolithic period (ca. 9500–4500 BCE). Six primary clay deposit types are represented—alluvial, residual terra rossa, basaltic soil, coastal hamra, Lisan Formation marl, and rendzina—drawn from 31 archaeological sites across 21 physiographic regions spanning the Jordan Valley, coastal plain, hill country, and Transjordanian plateau.
All quantitative distributions are calibrated to published archaeometric, geochemical, and geological data from the region, ensuring scientific plausibility and internal consistency across sheets. Geochemical variables are modelled with appropriate log-normal distributions and inter-variable covariance structures reflecting the actual correlations observed in published Levantine clay and ceramic compositional datasets.
The following sections present each sheet in sequential order, providing a narrative description of the sheet’s purpose and scientific context followed by a detailed table defining every column including its data type, expected range, and interpretive significance.
 
2. Dataset Summary
Sheet #	Sheet Name	Domain	Rows	Columns
1	Major_Oxide_Geochem	Major oxide geochemistry (SiO₂–LOI)	5,000	21
2	Trace_Element_Anal	Trace elements (Ba–U, 15 elements)	5,000	22
3	REE_Profiles	Rare earth elements (La–Lu + ratios)	5,000	23
4	Clay_Mineralogy_XRD	Clay minerals and XRD diagnostics	5,000	20
5	Petrographic_Anal	Ceramic thin-section petrography	5,000	19
6	Ceramic_Sherd_Chem	Ceramic body major oxide chemistry	5,000	19
7	Weathering_Indices	Chemical weathering indices and ratios	5,000	20
8	Physical_Properties	Geotechnical and physical properties	5,000	19
9	NAA_Results	Neutron Activation Analysis data	5,000	23
10	XRF_Results	X-Ray Fluorescence major oxides	5,000	19
11	ICP_MS_Results	ICP-MS extended trace elements	5,000	23
12	PCA_Scores	Principal Component Analysis scores	5,000	18
13	DFA_Classification	Discriminant Function Analysis results	5,000	17
14	Site_Catchment	Resource territory and catchment data	5,000	19
15	Production_Org	Craft organisation and production economy	5,000	20
16	Provenance_Assign	Integrated provenance determinations	5,000	18
17	Firing_Temp_Est	Firing temperature estimation	5,000	19
18	Grain_Size_Distrib	Particle size distribution analysis	5,000	21

 
3. Sheet 1: Major Oxide Geochemistry
3.1 Sheet Overview
This sheet constitutes the foundational geochemical dataset, containing major oxide compositions (expressed as weight percentages) for 5,000 clay deposit samples collected across the Southern Levant. The data are calibrated to published analytical ranges for six primary clay deposit types exploited by Neolithic potters: residual terra rossa, alluvial clays, basaltic soils, coastal hamra, Lisan Formation marls, and rendzina soils. Each sample is georeferenced to one of 31 archaeological sites spanning the Pre-Pottery Neolithic through Late Neolithic periods. The oxide triad of CaO, Al2O3, and Fe2O3 serves as the primary discriminator between alluvial (high CaO, moderate Al2O3) and residual (low CaO, high Al2O3 and Fe2O3) deposit types, reflecting the fundamental geochemical divergence arising from differential weathering histories and sedimentary transport processes.
Sheet Name in Workbook: Major_Oxide_Geochemistry
Total Records: 5,000 rows
Total Columns: 21

3.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique alphanumeric identifier for each sample in the format MOX-XXXXX, where MOX denotes the Major Oxide dataset and the five-digit suffix provides sequential enumeration. This identifier enables cross-referencing across all 18 sheets within the workbook.
Site_Name	Full archaeological site name as established in the published literature (e.g., Sha'ar Hagolan, Jericho, Ain Ghazal). Names follow the conventional English transliterations adopted by the Israel Antiquities Authority and the Department of Antiquities of Jordan.
Site_Code	Three-letter abbreviated site code for compact data representation in statistical analyses and bivariate plots (e.g., SHG for Sha'ar Hagolan, JER for Jericho, ANG for Ain Ghazal).
Region	Physiographic region within the Southern Levant from which the sample originates. The dataset includes 21 distinct regions such as Central Jordan Valley, Hula Valley, Judean Hills, Southern Coastal Plain, and Transjordan Highlands, reflecting the geological and ecological diversity of the study area.
Period	Archaeological period assignment following the conventional Southern Levantine Neolithic chronological framework. Codes include PPNA (Pre-Pottery Neolithic A, ca. 9500–8500 BCE), EPPNB, MPPNB, LPPNB, PPNC, YAR (Yarmukian, ca. 6400–5800 BCE), LOD (Lodian), WR (Wadi Rabah), LN (Late Neolithic), and GH (Ghassulian/Early Chalcolithic).
Clay_Type	Classification of the clay deposit into one of six geochemically distinct categories: Alluvial (transported fluvial sediments), Residual_Terra_Rossa (in-situ weathering product of limestone/dolomite), Basaltic_Soil (derived from Neogene-Quaternary basalt), Coastal_Hamra (red loamy sand of the coastal plain), Lisan_Marl (lacustrine carbonate-detrital deposit), or Rendzina (shallow calcareous soil on chalk/marl substrates).
Deposit_Context	Sedimentological context describing the depositional environment of the clay source. Categories include Primary in-situ, Secondary reworked, Tertiary alluvial, Colluvial, Lacustrine, Fluvial terrace, Wadi bed, Paleosol, Active floodplain, and Residual hilltop.
Formation	Parent geological formation from which the clay deposit derives. Nine formations are represented: Lisan Fm, Samra Fm, Judea Group, Mt Scopus Group, Avedat Group, Kurkar Fm, Basalt Fm, Lower Cretaceous Shale, and Ze'elim Fm, each imparting distinct geochemical fingerprints onto derived clays.
Latitude	Geographic latitude of the sampling location in decimal degrees (WGS84 datum). Values include minor stochastic perturbation (σ = 0.005°) to simulate intra-site spatial variability among individual sampling points.
Longitude	Geographic longitude of the sampling location in decimal degrees (WGS84 datum), with the same stochastic perturbation applied as for latitude.
SiO2_wt%	Silicon dioxide concentration expressed as weight percent of the total oxide analysis. SiO2 ranges from approximately 15% (Lisan marls) to 65% (coastal hamra), reflecting the balance between detrital quartz/feldspar and authigenic clay minerals. Elevated SiO2 typically indicates quartz-rich sandy substrates or mature weathering profiles.
Al2O3_wt%	Aluminium oxide concentration (wt%). Al2O3 is the primary indicator of clay mineral abundance and weathering intensity, with terra rossa soils exhibiting the highest values (10–25%) due to extensive leaching of mobile cations and residual enrichment of aluminium in kaolinite and gibbsite.
Fe2O3_wt%	Total iron as ferric oxide (wt%). Fe2O3 is diagnostic for distinguishing basaltic-derived clays (8–15%) from calcareous sedimentary clays (2–6%). Iron occurs as hematite, goethite, and structural substitution in clay lattices, conferring the characteristic red coloration of terra rossa and hamra soils.
MgO_wt%	Magnesium oxide concentration (wt%). MgO is elevated in basaltic soils (3–8%) and alluvial clays with dolomitic contributions, while being low in mature terra rossa (0.5–3%) where magnesium has been leached during pedogenesis.
CaO_wt%	Calcium oxide concentration (wt%). CaO is the most powerful single discriminator between alluvial and residual deposits. Lisan marls exhibit extreme CaO enrichment (25–45%) reflecting primary carbonate precipitation, alluvial clays show moderate values (5–25%) from inherited calcite, while terra rossa clays are strongly decalcified (0.5–15%).
Na2O_wt%	Sodium oxide concentration (wt%). Na2O is generally low across all deposit types (0.1–2.0%), with slightly elevated values in basaltic soils reflecting the sodic character of alkali olivine basalt parent material and in alluvial clays influenced by evaporitic contributions.
K2O_wt%	Potassium oxide concentration (wt%). K2O reflects illite abundance and feldspar content, ranging from 0.5–3.0% across deposit types. Elevated K2O in terra rossa and alluvial clays correlates with illite preservation in the clay fraction.
TiO2_wt%	Titanium dioxide concentration (wt%). TiO2 is a key provenance indicator due to the immobility of titanium during weathering. Basaltic soils exhibit the highest TiO2 (1.5–3.5%) reflecting the titaniferous character of the basaltic parent rock, while Lisan marls show the lowest values (0.2–0.8%).
P2O5_wt%	Phosphorus pentoxide concentration (wt%). P2O5 is influenced by both geological (apatite content) and anthropogenic (bone, ash, organic waste) inputs. Basaltic soils show the highest geological P2O5 (0.2–1.0%), while elevated values in archaeological contexts may indicate contamination from habitation deposits.
MnO_wt%	Manganese oxide concentration (wt%). MnO is a minor but diagnostically useful component, with basaltic soils showing the highest concentrations (0.15–0.30%) reflecting the manganese-enriched character of basaltic parent material. Redox-sensitive behaviour makes MnO a secondary indicator of drainage conditions.
LOI_wt%	Loss on ignition at 1000°C expressed as weight percent. LOI encompasses combined water (from clay mineral dehydroxylation), organic matter, and CO2 from carbonate decomposition. Lisan marls exhibit the highest LOI (20–35%) due to their high carbonate content, while basaltic soils show the lowest (5–12%).
 
4. Sheet 2: Trace Element Analysis
4.1 Sheet Overview
This sheet presents trace element concentrations measured in parts per million (ppm) for 5,000 clay samples. Trace elements provide substantially higher discriminatory power than major oxides for distinguishing clay source provenance because many trace elements are geochemically immobile during weathering and thus preserve the signature of the parent lithology. The dataset incorporates 15 trace elements routinely measured in ceramic provenance studies, with distributions calibrated to published Neutron Activation Analysis (NAA), X-Ray Fluorescence (XRF), and Inductively Coupled Plasma Mass Spectrometry (ICP-MS) data from the region. The chromium-nickel-vanadium-cobalt quartet (Cr, Ni, V, Co) constitutes the most powerful discriminator for basaltic versus non-basaltic clay sources, while the rubidium-barium-strontium system discriminates among sedimentary clay types.
Sheet Name in Workbook: Trace_Element_Anal
Total Records: 5,000 rows
Total Columns: 22

4.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format TRC-XXXXX for the Trace Element dataset.
Site_Name	Full archaeological site name corresponding to one of the 31 Neolithic sites in the study area.
Site_Code	Three-letter site abbreviation.
Region	Physiographic region of origin within the Southern Levant.
Clay_Type	Geochemical clay deposit classification (Alluvial, Residual_Terra_Rossa, Basaltic_Soil, Coastal_Hamra, Lisan_Marl, Rendzina).
Formation	Parent geological formation.
Analytical_Method	Analytical technique employed for trace element determination. Options include INAA (Instrumental Neutron Activation Analysis), WD-XRF (Wavelength Dispersive X-Ray Fluorescence), ICP-MS (Inductively Coupled Plasma Mass Spectrometry), ICP-OES (Inductively Coupled Plasma Optical Emission Spectrometry), pXRF (portable XRF), and LA-ICP-MS (Laser Ablation ICP-MS).
Ba_ppm	Barium concentration in parts per million. Ba substitutes for potassium in feldspars and micas, with values ranging from 150 to 500 ppm across deposit types. Ba/Sr ratios are used as weathering intensity proxies.
Sr_ppm	Strontium concentration (ppm). Sr substitutes for calcium in carbonate and plagioclase, producing elevated values (200–700 ppm) in calcareous clays (Lisan marl, rendzina) and lower values in decalcified residual soils.
Zr_ppm	Zirconium concentration (ppm). Zr resides almost exclusively in detrital zircon, making it a robust provenance tracer unaffected by weathering or diagenesis. Values range from 100 to 350 ppm.
Rb_ppm	Rubidium concentration (ppm). Rb substitutes for potassium in illite and K-feldspar. Residual terra rossa clays exhibit the highest Rb (50–120 ppm) reflecting clay mineral enrichment, while basaltic soils show the lowest (10–40 ppm).
Cr_ppm	Chromium concentration (ppm). Cr is the single most diagnostic element for identifying basaltic clay provenance, with values of 150–600 ppm in basaltic soils versus 30–150 ppm in all other deposit types. Cr resides in chromite, pyroxene, and Cr-spinel.
Ni_ppm	Nickel concentration (ppm). Ni co-varies strongly with Cr in basaltic provenance contexts (80–350 ppm in basaltic soils), residing in olivine, pyroxene, and secondary Ni-bearing smectites.
V_ppm	Vanadium concentration (ppm). V is enriched in mafic minerals and magnetite, producing elevated values (150–350 ppm) in basaltic soils. V co-varies with Fe2O3 and TiO2 across all deposit types.
Co_ppm	Cobalt concentration (ppm). Co completes the mafic element quartet (Cr-Ni-V-Co), with basaltic soils showing 30–70 ppm versus 6–25 ppm in non-basaltic clays.
Cu_ppm	Copper concentration (ppm). Cu ranges from 10–120 ppm, with highest values in basaltic soils. Anomalously elevated Cu may indicate anthropogenic contamination from metallurgical activities in later periods.
Zn_ppm	Zinc concentration (ppm). Zn ranges from 30–180 ppm and is moderately elevated in basaltic soils. Like Cu, anomalous Zn enrichment may signal post-depositional anthropogenic input.
Pb_ppm	Lead concentration (ppm). Pb is typically low (5–40 ppm) in Neolithic contexts, with slightly higher values in felsic-derived clays (terra rossa, rendzina) due to the lithophile behaviour of Pb in granitic/sedimentary systems.
Y_ppm	Yttrium concentration (ppm). Y behaves as a pseudo-heavy rare earth element (HREE) and ranges from 12–35 ppm. Y is useful in provenance bivariate plots such as Y/Nb versus Zr/Nb.
Nb_ppm	Niobium concentration (ppm). Nb is strongly enriched in basaltic soils (15–45 ppm) relative to sedimentary clays (5–18 ppm), reflecting the incompatible-element-enriched character of alkali basalt.
Th_ppm	Thorium concentration (ppm). Th is enriched in felsic/sedimentary-derived clays (8–16 ppm in terra rossa) relative to mafic sources (3–8 ppm in basaltic soils). The Th/Sc ratio is a standard upper continental crust (UCC) normalization proxy.
U_ppm	Uranium concentration (ppm). U ranges from 1–6 ppm and is slightly elevated in calcareous deposits (rendzina, Lisan) due to uranium co-precipitation with carbonate phases.
 
5. Sheet 3: Rare Earth Element (REE) Profiles
5.1 Sheet Overview
This sheet provides complete rare earth element profiles for all 14 lanthanides (La through Lu) plus derived REE ratios and anomaly indices for 5,000 samples. REE patterns are among the most powerful provenance discriminators in geochemistry because the entire lanthanide series behaves coherently during geological processes, with systematic fractionation controlled by ionic radius. The chondrite-normalized REE patterns of Southern Levantine clays exhibit characteristic light-REE (LREE) enrichment, negative europium anomalies (reflecting feldspar fractionation in source rocks), and variable LREE/HREE ratios that distinguish basaltic (lower, flatter patterns) from felsic/sedimentary (steeper, more LREE-enriched patterns) provenance. Total REE abundances range from approximately 100 to 250 ppm.
Sheet Name in Workbook: REE_Profiles
Total Records: 5,000 rows
Total Columns: 23

5.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format REE-XXXXX.
Site_Code	Three-letter site abbreviation.
Clay_Type	Geochemical clay deposit classification.
Region	Physiographic region of origin.
Formation	Parent geological formation.
La_ppm	Lanthanum concentration (ppm). La is the lightest and most abundant REE, ranging from approximately 15–65 ppm. La anchors the LREE end of the chondrite-normalized pattern.
Ce_ppm	Cerium concentration (ppm). Ce is typically the most abundant REE (30–130 ppm) and may exhibit positive or negative Ce anomalies under oxidizing conditions due to Ce³⁺/Ce⁴⁺ redox cycling.
Pr_ppm	Praseodymium concentration (ppm). Pr ranges from approximately 4–16 ppm and follows the smooth LREE trend between Ce and Nd.
Nd_ppm	Neodymium concentration (ppm). Nd ranges from approximately 15–60 ppm and is widely used in isotopic provenance studies (Nd isotopes) when available.
Sm_ppm	Samarium concentration (ppm). Sm marks the transition from LREE to middle REE (MREE), ranging from approximately 3–12 ppm. Sm is essential for calculating the Eu anomaly (Eu/Eu*).
Eu_ppm	Europium concentration (ppm). Eu ranges from approximately 0.6–2.3 ppm and characteristically displays a negative anomaly (Eu depletion relative to Sm and Gd) in clays derived from evolved crustal sources. Basaltic clays show a weaker negative anomaly.
Gd_ppm	Gadolinium concentration (ppm). Gd is the first HREE-group element, ranging from approximately 3–10 ppm. Gd is required for the Eu anomaly calculation and the Gd/Yb fractionation ratio.
Tb_ppm	Terbium concentration (ppm). Tb ranges from approximately 0.4–1.3 ppm and follows the smooth HREE declination trend.
Dy_ppm	Dysprosium concentration (ppm). Dy ranges from approximately 2.5–8 ppm.
Ho_ppm	Holmium concentration (ppm). Ho ranges from approximately 0.5–1.5 ppm.
Er_ppm	Erbium concentration (ppm). Er ranges from approximately 1.5–4.5 ppm.
Tm_ppm	Thulium concentration (ppm). Tm ranges from approximately 0.2–0.7 ppm and is the least abundant REE measured in routine analyses.
Yb_ppm	Ytterbium concentration (ppm). Yb ranges from approximately 1.5–4.0 ppm and anchors the HREE end of the chondrite-normalized pattern. The La/Yb ratio (chondrite-normalized) is a fundamental fractionation metric.
Lu_ppm	Lutetium concentration (ppm). Lu is the heaviest and least abundant REE, ranging from approximately 0.2–0.6 ppm.
Eu_Eu_star	Europium anomaly calculated as Eu/Eu* = Eu_CN / sqrt(Sm_CN × Gd_CN), where CN denotes chondrite-normalized values. Values less than 1.0 indicate a negative Eu anomaly (typical of felsic/crustal sources), while values near 1.0 suggest mafic/basaltic sources. Expected range: 0.40–1.10.
LaN_YbN	Chondrite-normalized La/Yb ratio, a measure of LREE/HREE fractionation. Higher values (7–12) indicate steeper REE patterns typical of felsic/sedimentary-derived clays, while lower values (5–8) indicate flatter patterns characteristic of basaltic sources.
LREE_HREE	Ratio of total light rare earth elements (La+Ce+Pr+Nd) to total heavy rare earth elements (Er+Tm+Yb+Lu). This ratio provides a bulk measure of REE fractionation, with higher values indicating greater LREE enrichment.
Total_REE_ppm	Sum of all 14 measured REE concentrations (La through Lu) expressed in parts per million. Total REE abundance is a first-order indicator of clay mineral concentration and source rock composition, typically ranging from 100–250 ppm.
 
6. Sheet 4: Clay Mineralogy and X-Ray Diffraction (XRD) Data
6.1 Sheet Overview
This sheet records the mineralogical composition of 5,000 clay samples as determined by X-ray diffraction analysis. Clay mineral assemblages in the Southern Levant follow systematic patterns governed by parent lithology, drainage conditions, and climate. Well-drained residual soils (terra rossa) undergo progressive kaolinitization, yielding high kaolinite percentages (20–60%), while poorly drained alluvial settings and basaltic soils preserve smectite as the dominant clay mineral (50–90% of the clay fraction). The sheet includes both clay fraction minerals (kaolinite, illite, smectite/interstratified illite-smectite, chlorite, palygorskite) and non-clay minerals (quartz, feldspar, calcite, dolomite, hematite, goethite), along with XRD diagnostic parameters such as crystallinity indices and d-spacing values.
Sheet Name in Workbook: Clay_Mineralogy_XRD
Total Records: 5,000 rows
Total Columns: 20

6.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format XRD-XXXXX.
Site_Code	Three-letter site abbreviation.
Region	Physiographic region of origin.
Clay_Type	Geochemical clay deposit classification.
Formation	Parent geological formation.
Depth_cm	Sampling depth below the modern ground surface in centimetres. Depth influences clay mineral assemblages through profile weathering gradients, with surface horizons typically showing more advanced weathering (higher kaolinite) than subsurface horizons.
Kaolinite_%	Percentage of kaolinite in the clay mineral fraction. Kaolinite is the product of advanced silicate weathering under well-drained acidic conditions. Terra rossa soils exhibit the highest kaolinite content (20–60%), while alluvial and basaltic soils show lower values (10–25%).
Illite_%	Percentage of illite in the clay mineral fraction. Illite is a detrital mineral inherited from parent sedimentary rocks and is most abundant in terra rossa (15–30%) and alluvial clays (5–15%) derived from Cretaceous limestone/marl substrates.
Smectite_IS_%	Combined percentage of smectite and interstratified illite-smectite (IS) in the clay fraction. This is the dominant clay mineral in most Southern Levantine soils, ranging from 15–40% in evolved terra rossa to greater than 60% in basaltic soils and alluvial deposits. Random (R0) interstratification is most common.
Chlorite_%	Percentage of chlorite in the clay fraction. Chlorite is a minor component (trace to 5%) across all deposit types, predominantly of detrital origin. Chlorite is distinguished from kaolinite by its survival at 550°C during heating treatments.
Palygorskite_%	Percentage of palygorskite (attapulgite) in the clay fraction. Palygorskite is an authigenic fibrous clay mineral forming under arid, alkaline, Mg-rich conditions. It is characteristic of rendzina soils (5–15%) and Lisan/loess deposits (3–8%), while being absent from terra rossa and basaltic soils.
Quartz_%	Percentage of quartz in the bulk mineral assemblage. Quartz is the dominant non-clay mineral, ranging from 10–20% in Lisan marls to 50–80% in coastal hamra soils, reflecting the relative proportion of detrital versus chemical sedimentary components.
Feldspar_%	Percentage of feldspar (combined plagioclase and K-feldspar) in the bulk assemblage. Feldspar ranges from 3–12% and is slightly elevated in alluvial and basaltic soils.
Calcite_%	Percentage of calcite in the bulk assemblage. Calcite is a primary discriminator, ranging from near zero in decalcified terra rossa to 25–50% in Lisan marls.
Dolomite_%	Percentage of dolomite in the bulk assemblage. Dolomite is present at 0–10% and is most abundant in alluvial and Lisan deposits influenced by dolomitic parent rock.
Hematite_%	Percentage of hematite in the bulk assemblage. Hematite is the iron oxide responsible for the red pigmentation of terra rossa soils (2–6%) and is less abundant in reduced or calcareous environments.
Goethite_%	Percentage of goethite in the bulk assemblage. Goethite is a hydrated iron oxyhydroxide present at 0–2%, more common in periodically waterlogged soils.
Crystallinity_Index	XRD-derived crystallinity index for the dominant clay mineral, calculated from peak width at half-maximum (FWHM). Values range from 0.30 (poorly crystalline) to 0.95 (well crystalline). Higher crystallinity indicates better-ordered clay structures.
d001_Smectite_A	Basal d-spacing of smectite measured under air-dried (AD) conditions in Angstroms. Expected values are 14–15 Å for Ca-smectite and 12–13 Å for Na-smectite.
EG_d001_A	Basal d-spacing of smectite after ethylene glycol (EG) solvation in Angstroms. Expected value is approximately 17 Å for expandable smectite. Failure to expand fully may indicate mixed-layer (illite-smectite) ordering.
 
7. Sheet 5: Petrographic Analysis of Ceramic Thin Sections
7.1 Sheet Overview
This sheet records petrographic observations from optical microscopy of 5,000 ceramic thin sections. Petrography is the primary method for identifying temper type, fabric group, and manufacturing technology in archaeological ceramics. Neolithic Southern Levantine pottery is characterised by low firing temperatures (predominantly 500–750°C), open-pit/bonfire firing, and the use of locally available tempering materials. Eight fabric groups are defined based on the dominant temper type and matrix characteristics, following the classification framework established by Goren and colleagues for Levantine ceramic petrography. The sheet captures both compositional variables (temper type, matrix/void proportions) and textural parameters (grain size, sorting, roundness, optical activity) essential for fabric classification.
Sheet Name in Workbook: Petrographic_Anal
Total Records: 5,000 rows
Total Columns: 19

7.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format PTR-XXXXX.
Site_Code	Three-letter site abbreviation.
Region	Physiographic region of origin.
Period	Archaeological period code.
Vessel_Type	Morphological vessel form classification. Categories include Bowl, Jar, Cooking Pot, Storage Vessel, Jug, Platter, Krater, Hole-Mouth Jar, Miniature Vessel, and Fenestrated Bowl, reflecting the standard typological repertoire of Neolithic Southern Levantine ceramics.
Fabric_Group	Petrographic fabric group assignment based on temper mineralogy and matrix characteristics. Eight groups are defined: FG-1 (Calcareous Fine), FG-2 (Basalt Tempered), FG-3 (Sandy Coarse), FG-4 (Organic Tempered), FG-5 (Grog Tempered), FG-6 (Mixed Alluvial), FG-7 (Terra Rossa Fine), and FG-8 (Lisan Marl).
Primary_Temper	Dominant non-plastic inclusion type identified in the thin section. Categories include Calcite, Basalt, Straw/Organic, Sand/Quartz, and Grog, representing the five most common tempering materials in Neolithic pottery of the region.
Secondary_Temper	Subordinate non-plastic inclusion type, if present. May include any of the primary temper categories plus Shell, Flint/Chert, or None if only a single temper type is identified.
Temper_Vol_%	Volume percentage of non-plastic inclusions (temper) estimated by point-counting in the thin section. Values range from 5–40%, with most Neolithic sherds falling between 10–25%.
Matrix_Vol_%	Volume percentage of the fine-grained clay matrix estimated by point-counting. Values range from 40–80%, inversely correlated with temper and void proportions.
Void_Vol_%	Volume percentage of voids (porosity) estimated by point-counting. Values range from 5–35%, with higher porosity characteristic of low-fired, organic-tempered wares where straw burnout creates secondary voids.
Max_Grain_mm	Maximum grain size of non-plastic inclusions measured in millimetres. Values range from 0.5–5.0 mm, with basalt-tempered and calcite-tempered wares exhibiting the coarsest inclusions.
Mean_Grain_mm	Mean grain size of non-plastic inclusions in millimetres, calculated from the measured grain size distribution. Values range from 0.1–2.0 mm.
Sorting	Qualitative assessment of the uniformity of temper grain sizes: Well sorted, Moderately sorted, Poorly sorted, or Very poorly sorted. Well-sorted temper suggests intentional crushing and sieving, while poor sorting may indicate natural inclusions.
Roundness	Grain shape classification using the Powers (1953) scale: Angular, Sub-angular, Sub-rounded, Rounded, or Well-rounded. Angular grains indicate intentional crushing of temper, while rounded grains suggest natural alluvial transport.
Optical_Activity	Degree of birefringence of the clay matrix under crossed polars: Optically active (low firing, clay structure intact), Slightly active (intermediate firing), or Optically inactive (high firing, clay structure destroyed). This parameter is a primary indicator of firing temperature in the thin section.
Est_Firing_Temp_C	Estimated original firing temperature in degrees Celsius, derived from the combination of optical activity, mineral transformation indicators, and matrix coloration. The majority of Neolithic samples cluster between 500–750°C.
Firing_Atmosphere	Inferred firing atmosphere based on cross-section coloration and mineralogy: Oxidizing (uniform red/orange), Reducing (uniform grey/black), or Mixed/Incomplete (sandwich structure with dark core and oxidized margins).
Birefringence	Qualitative assessment of matrix birefringence intensity: High (indicating firing below approximately 550°C with preserved clay crystal structure), Moderate (550–700°C with partial structural collapse), Low (700–850°C), or None (above approximately 850°C with complete amorphisation).
 
8. Sheet 6: Ceramic Sherd Chemistry
8.1 Sheet Overview
This sheet presents major oxide analyses of 5,000 ceramic sherds, as distinct from the raw clay analyses in Sheet 1. The critical difference is that ceramic compositions reflect the combined chemistry of the clay matrix diluted by the addition of non-plastic temper materials. Calcite temper addition increases CaO by 2–18%, basalt temper elevates Fe2O3 and TiO2, and organic temper reduces all oxide concentrations proportionally through dilution. A stochastic dilution factor (0.72–0.95) has been applied to simulate the tempering process, enabling researchers to model temper correction algorithms for provenance attribution.
Sheet Name in Workbook: Ceramic_Sherd_Chem
Total Records: 5,000 rows
Total Columns: 19

8.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format CSC-XXXXX for Ceramic Sherd Chemistry.
Site_Name	Full archaeological site name.
Site_Code	Three-letter site abbreviation.
Period	Archaeological period code.
Vessel_Type	Morphological vessel form classification.
Temper_Type	Primary temper material identified in the sherd (Calcite, Basalt, Straw/Organic, Sand/Quartz, or Grog).
Clay_Source_Type	Inferred clay source type based on geochemical composition after temper correction.
SiO2_wt%	Silicon dioxide concentration in the ceramic sherd (wt%). Values are reduced relative to raw clay by the temper dilution factor and may be further modified by temper-specific contributions (e.g., elevated SiO2 from quartz sand temper).
Al2O3_wt%	Aluminium oxide concentration in the ceramic sherd (wt%). Al2O3 is diluted proportionally by temper addition and is not significantly contributed by common temper types.
Fe2O3_wt%	Iron oxide concentration in the ceramic sherd (wt%). Fe2O3 may be elevated above the dilution baseline in basalt-tempered sherds due to iron-rich basalt fragment contributions.
MgO_wt%	Magnesium oxide in the ceramic sherd (wt%).
CaO_wt%	Calcium oxide in the ceramic sherd (wt%). CaO is characteristically elevated (often by 2–18% above the clay baseline) in calcite-tempered sherds, which constitute the majority of Yarmukian ceramic assemblages. This temper-derived CaO must be corrected before provenance attribution.
Na2O_wt%	Sodium oxide in the ceramic sherd (wt%).
K2O_wt%	Potassium oxide in the ceramic sherd (wt%).
TiO2_wt%	Titanium dioxide in the ceramic sherd (wt%). May be slightly elevated in basalt-tempered sherds.
P2O5_wt%	Phosphorus pentoxide in the ceramic sherd (wt%).
MnO_wt%	Manganese oxide in the ceramic sherd (wt%).
LOI_wt%	Loss on ignition for the ceramic sherd (wt%). LOI is significantly reduced compared to raw clay because the firing process has already driven off much of the volatile content (water, organics, some carbonate CO2).
Analytical_Method	Analytical technique used for the sherd analysis (INAA, WD-XRF, ICP-MS, ICP-OES, pXRF, or LA-ICP-MS).
 
9. Sheet 7: Chemical Weathering Indices
9.1 Sheet Overview
This sheet compiles 5,000 records of chemical weathering indices and elemental ratios that serve as quantitative proxies for the degree of chemical alteration experienced by clay deposits. Weathering indices are the most robust geochemical discriminators between alluvial (transported, incompletely weathered, multi-source) and residual (in-situ, intensely weathered, single-source) clay deposits. The Chemical Index of Alteration (CIA) is the most widely applied metric, with values above 80 strongly indicating residual weathering profiles (terra rossa, basaltic soils) and values of 60–80 characterising alluvial sediments of mixed provenance. The dataset includes six weathering indices plus eight diagnostic elemental ratios.
Sheet Name in Workbook: Weathering_Indices
Total Records: 5,000 rows
Total Columns: 20

9.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format WTH-XXXXX.
Site_Code	Three-letter site abbreviation.
Region	Physiographic region of origin.
Clay_Type	Geochemical clay deposit classification.
Formation	Parent geological formation.
Deposit_Type	Simplified deposit genesis classification: Residual (in-situ weathering product), Alluvial (transported by water), or Mixed (intermediate/ambiguous origin).
CIA	Chemical Index of Alteration, calculated as 100 × [Al2O3 / (Al2O3 + CaO* + Na2O + K2O)], where CaO* represents calcium in silicate minerals only. CIA values range from approximately 55 (unweathered) to 100 (completely weathered). Residual terra rossa clays exhibit values of 75–95, while alluvial clays show values of 60–80.
CIW	Chemical Index of Weathering, calculated as 100 × [Al2O3 / (Al2O3 + CaO* + Na2O)]. CIW excludes K2O to eliminate the influence of illite, making it more sensitive to feldspar weathering. Residual clays show values of 80–100.
PIA	Plagioclase Index of Alteration, calculated as 100 × [(Al2O3 – K2O) / (Al2O3 + CaO* + Na2O – K2O)]. PIA specifically targets plagioclase weathering and ranges from approximately 50 (fresh) to 100 (completely weathered).
WIP	Weathering Index of Parker, calculated from the proportional contributions of Na, Mg, K, and Ca normalised by their bond strengths. WIP decreases with increasing weathering intensity, with values of 15–40 for residual clays and 40–80 for alluvial clays.
Vogt_V_Ratio	Vogt Ratio calculated as (Al2O3 + K2O) / (MgO + CaO + Na2O). Values greater than 2 indicate advanced weathering with preferential retention of aluminium and potassium, characteristic of residual terra rossa deposits.
SiO2_Al2O3	Molar ratio of SiO2 to Al2O3, a proxy for clay mineral maturity. Lower ratios indicate more aluminous (kaolinite-rich) clays characteristic of advanced weathering.
Al2O3_TiO2	Ratio of Al2O3 to TiO2, used as a source rock composition proxy because both elements are relatively immobile during weathering. Values vary with parent lithology.
K2O_Na2O	Ratio of K2O to Na2O, reflecting the relative mobility of sodium (highly mobile) versus potassium (moderately mobile, retained in illite) during weathering.
Fe2O3_MgO	Ratio of Fe2O3 to MgO, useful for distinguishing between iron-enriched residual soils (high ratio) and Mg-bearing alluvial/basaltic clays (lower ratio).
Rb_Sr	Ratio of Rb to Sr concentrations. This ratio increases with weathering intensity as Sr (hosted in carbonate and plagioclase) is leached preferentially while Rb (hosted in illite) is retained. Residual clays show higher Rb/Sr (approximately 0.25–0.50) than alluvial clays (0.10–0.25).
La_Sc	Ratio of La to Sc, a standard provenance discrimination ratio. La/Sc increases in felsic/sedimentary sources and decreases in mafic sources.
Th_Sc	Ratio of Th to Sc, another felsic versus mafic provenance discriminator. Higher values indicate felsic-dominated provenance.
Cr_V	Ratio of Cr to V. This ratio is elevated (greater than 1.5) in basaltic soils due to extreme Cr enrichment and approximately 0.5–1.0 in non-basaltic clays.
ICV	Index of Compositional Variability, calculated as (Fe2O3 + K2O + Na2O + CaO + MgO + MnO + TiO2) / Al2O3. ICV values less than 1.0 indicate compositionally mature, recycled sediments (residual clays), while values greater than 1.0 indicate first-cycle, immature sediments (alluvial clays).
 
10. Sheet 8: Physical and Geotechnical Properties
10.1 Sheet Overview
This sheet documents the physical, geotechnical, and colorimetric properties of 5,000 clay samples. These parameters are directly relevant to the practical suitability of a clay deposit for ceramic production: plasticity determines workability, particle size controls texture, pH influences firing behaviour, and cation exchange capacity (CEC) reflects clay mineral type and abundance. The data enable assessment of which deposits within each site’s catchment territory would have been most attractive to Neolithic potters, who required clays with moderate plasticity (Plasticity Index 10–30), adequate clay content (greater than 20%), and manageable shrinkage behaviour.
Sheet Name in Workbook: Physical_Properties
Total Records: 5,000 rows
Total Columns: 19

10.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format PHY-XXXXX.
Site_Code	Three-letter site abbreviation.
Region	Physiographic region of origin.
Clay_Type	Geochemical clay deposit classification.
Depth_cm	Sampling depth below the modern ground surface in centimetres.
Clay_pct_lt2um	Percentage of particles smaller than 2 micrometres in the total sample, representing the clay-size fraction. Terra rossa and basaltic soils exhibit the highest clay content (50–70%), while coastal hamra soils show the lowest (10–25%).
Silt_pct_2_63um	Percentage of particles between 2 and 63 micrometres (silt fraction). Silt typically comprises 20–40% of most deposit types, with loess deposits showing the highest silt content.
Sand_pct_gt63um	Percentage of particles larger than 63 micrometres (sand fraction). Sand content is inversely related to clay content, ranging from less than 5% in heavy clay soils to 40–60% in hamra deposits.
Liquid_Limit_%	Atterberg Liquid Limit: the gravimetric water content at which the soil transitions from a plastic to a liquid state. Values range from approximately 20–120%, with smectite-rich clays exhibiting the highest values due to their high water adsorption capacity.
Plastic_Limit_%	Atterberg Plastic Limit: the water content at which the soil transitions from a semi-solid to a plastic state. Values range from approximately 10–55%.
Plasticity_Index	Plasticity Index (PI = Liquid Limit – Plastic Limit), the range of water content over which the clay is workable. Optimal values for hand-built pottery are approximately 10–30%. Very high PI values (greater than 40) indicate excessively sticky, difficult-to-work clays.
Shrinkage_Limit_%	Shrinkage Limit: the water content below which further drying causes no additional volume decrease. Values range from 6–30%. Low shrinkage limits in smectite-rich clays indicate high susceptibility to drying cracks during pottery manufacture.
pH	Soil pH measured in a 1:2.5 soil:water suspension. Values range from approximately 5.5–9.0, with calcareous deposits (rendzina, alluvial, Lisan) showing alkaline pH (7.5–8.5) and decalcified terra rossa showing slightly acidic to neutral pH (6.5–7.5).
CEC_meq_100g	Cation Exchange Capacity in milliequivalents per 100 grams of soil. CEC reflects clay mineral type and abundance: smectite-rich basaltic soils and terra rossa show the highest CEC (30–60 meq/100g), while quartz-dominated hamra deposits show the lowest (3–15 meq/100g).
Organic_Matter_%	Percentage of organic matter determined by loss on ignition at 400°C or Walkley-Black method. Values range from 0.1–12%, with alluvial valley floor deposits showing the highest organic content.
Munsell_Dry	Munsell colour notation of the dry sample (e.g., 2.5YR 4/6 denotes Hue 2.5YR, Value 4, Chroma 6). Red hues (2.5YR–5YR) characterise iron-rich terra rossa and hamra, while dark grayish-brown hues (10YR–2.5Y) characterise alluvial and basaltic soils.
Munsell_Wet	Munsell colour notation of the wet/moist sample, typically 1–2 value units darker than the dry colour.
Specific_Gravity	Specific gravity (particle density) of the clay solid phase, typically 2.55–2.80 for mineral soils. Higher values indicate iron-rich mineral phases; lower values may indicate organic enrichment.
Mean_Grain_Phi	Mean grain size expressed in phi (φ) units where φ = –log2(diameter in mm). Higher phi values correspond to finer grain sizes. Clay-dominated deposits show mean phi values of 7–10, while silty/sandy deposits show values of 4–6.
 
11. Sheet 9: Neutron Activation Analysis (NAA) Results
11.1 Sheet Overview
This sheet contains Instrumental Neutron Activation Analysis (INAA) data for 5,000 samples, formatted to conform to the standard reporting protocols of the major Levantine ceramic provenance laboratories (Bonn, Hebrew University of Jerusalem, Missouri University Research Reactor). NAA remains the gold standard for ceramic provenance determination due to its exceptional precision (1–5% RSD for most elements), multi-element capability (25–35 elements simultaneously), and minimal sample requirements (80–200 mg). The data include both major elements reported as weight percent and trace/REE elements reported in ppm, along with laboratory metadata (irradiation codes, sample mass).
Sheet Name in Workbook: NAA_Results
Total Records: 5,000 rows
Total Columns: 23

11.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format NAA-XXXXX.
Site_Code	Three-letter site abbreviation.
Region	Physiographic region of origin.
Clay_Type	Geochemical clay deposit classification.
Sample_Mass_mg	Mass of the sample pellet submitted for irradiation, in milligrams. Standard NAA protocols require 80–200 mg of homogenised, dried, powdered material.
Irradiation_Code	Unique alphanumeric code identifying the specific neutron irradiation batch (format IRR-XXXX). Samples within the same irradiation batch share identical neutron flux conditions, enabling batch-level quality control.
Al_%	Aluminium concentration reported as elemental weight percent (not Al2O3). Conversion factor: Al% = Al2O3% × 0.529.
Ca_%	Calcium concentration as elemental weight percent. Conversion factor: Ca% = CaO% × 0.714.
Fe_%	Iron concentration as elemental weight percent. Conversion factor: Fe% = Fe2O3% × 0.699.
K_%	Potassium concentration as elemental weight percent. Conversion factor: K% = K2O% × 0.830.
Na_%	Sodium concentration as elemental weight percent. Conversion factor: Na% = Na2O% × 0.742.
Ti_%	Titanium concentration as elemental weight percent. Conversion factor: Ti% = TiO2% × 0.599.
Mn_ppm	Manganese concentration in parts per million. Mn is determined with high precision by NAA due to the favourable nuclear properties of 55Mn.
Sc_ppm	Scandium concentration in parts per million. Sc is one of the most precisely determined elements by NAA and serves as a normalisation element for provenance ratios. Values range from approximately 5–35 ppm, with higher values in mafic (basaltic) sources.
Cr_ppm	Chromium concentration in parts per million, the primary basaltic provenance indicator.
Co_ppm	Cobalt concentration in parts per million.
Rb_ppm	Rubidium concentration in parts per million. Rb is determined by NAA through the 87Rb(n,γ)88Rb reaction.
Cs_ppm	Caesium concentration in parts per million. Cs is an important discriminator in ceramic provenance studies, with values of 2–10 ppm in Southern Levantine clays. Cs is retained in illite interlayer sites and increases with clay mineral maturity.
Ba_ppm	Barium concentration in parts per million.
La_ppm	Lanthanum concentration in parts per million. La is determined with high precision by NAA and is the primary LREE reference element.
Ce_ppm	Cerium concentration in parts per million.
Sm_ppm	Samarium concentration in parts per million. Sm is one of the most precisely determined REE by NAA.
Eu_ppm	Europium concentration in parts per million. Eu is determined with exceptional precision by NAA, making the Eu anomaly calculation highly reliable.
 
12. Sheet 10: X-Ray Fluorescence (XRF) Results
12.1 Sheet Overview
This sheet presents Wavelength Dispersive X-Ray Fluorescence (WD-XRF) major oxide analyses for 5,000 samples. XRF is the most widely used technique for routine major element analysis of geological and archaeological materials, offering rapid throughput, non-destructive or minimally destructive analysis, and high precision for major elements (1–3% RSD). The dataset includes instrument specifications, sample preparation methods, and complete major oxide profiles including SO3 and Cl, which are not routinely reported in other techniques. The analytical total provides a quality control metric for each analysis.
Sheet Name in Workbook: XRF_Results
Total Records: 5,000 rows
Total Columns: 19

12.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format XRF-XXXXX.
Site_Code	Three-letter site abbreviation.
Region	Physiographic region of origin.
Clay_Type	Geochemical clay deposit classification.
Instrument	Specific WD-XRF instrument model used for the analysis. Instruments include Bruker S8 Tiger, PANalytical Axios, Rigaku ZSX Primus, and Thermo ARL PERFORM'X, each with characteristic analytical configurations.
Prep_Method	Sample preparation method: Fused bead (lithium tetraborate fusion, preferred for accurate major element analysis eliminating mineralogical matrix effects) or Pressed pellet (ground powder compressed into a disc, faster but subject to particle size and mineralogical effects).
SiO2_%	Silicon dioxide concentration by XRF (wt%).
Al2O3_%	Aluminium oxide concentration by XRF (wt%).
Fe2O3_%	Total iron as Fe2O3 by XRF (wt%).
MgO_%	Magnesium oxide concentration by XRF (wt%).
CaO_%	Calcium oxide concentration by XRF (wt%).
Na2O_%	Sodium oxide concentration by XRF (wt%). Note: Na2O determination by XRF is less precise than by NAA or ICP due to its low atomic number.
K2O_%	Potassium oxide concentration by XRF (wt%).
TiO2_%	Titanium dioxide concentration by XRF (wt%).
P2O5_%	Phosphorus pentoxide concentration by XRF (wt%).
MnO_%	Manganese oxide concentration by XRF (wt%).
SO3_%	Sulfur trioxide concentration by XRF (wt%). SO3 is not routinely reported in other techniques and reflects the presence of gypsum, pyrite oxidation products, or atmospheric sulfate deposition. Values range from 0–2%.
Cl_%	Chlorine concentration by XRF (wt%). Cl may be elevated in coastal and evaporitic deposit contexts and in ceramics exposed to saline groundwater.
Total_%	Analytical total of all reported oxides including LOI, expressed as a percentage. Acceptable totals fall between 98.5–101.5%, providing a quality control metric. Totals significantly outside this range indicate analytical problems or unreported volatile components.
 
13. Sheet 11: ICP-MS Results (Extended Trace Element Suite)
13.1 Sheet Overview
This sheet presents Inductively Coupled Plasma Mass Spectrometry (ICP-MS) data for an extended suite of trace elements for 5,000 samples. ICP-MS offers the broadest multi-element capability of any routine analytical technique, with detection limits at the sub-parts-per-billion level for most elements. The extended element suite includes lithophile (Li, Be, Ga), siderophile (Sc, V, Cr, Co, Ni), and chalcophile (Cu, Zn, Mo) elements plus the high-field-strength elements (Zr, Nb, Hf) that are particularly diagnostic for provenance determination. The digestion method is recorded because incomplete dissolution of refractory minerals (zircon, chromite) can produce systematic biases.
Sheet Name in Workbook: ICP_MS_Results
Total Records: 5,000 rows
Total Columns: 23

13.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format ICP-XXXXX.
Site_Code	Three-letter site abbreviation.
Clay_Type	Geochemical clay deposit classification.
Region	Physiographic region of origin.
Digestion_Method	Acid digestion protocol used to dissolve the solid sample prior to solution ICP-MS analysis. Options include HF-HNO3-HClO4 (complete dissolution including silicates), Aqua regia (partial dissolution, does not dissolve silicates), Li2B4O7 fusion (complete dissolution via lithium metaborate fusion), and HF-HNO3 (standard silicate dissolution without perchloric acid).
Li_ppm	Lithium concentration (ppm). Li substitutes for Mg in clay mineral octahedral sites. Values range from approximately 2–120 ppm.
Be_ppm	Beryllium concentration (ppm). Be is a lithophile trace element ranging from approximately 0.2–8 ppm. Be is enriched in felsic/evolved sources.
Sc_ppm	Scandium concentration (ppm). Sc is a key normalisation element for provenance ratios (La/Sc, Th/Sc, Cr/Sc), determined with high precision by ICP-MS. Range: 3–35 ppm.
V_ppm	Vanadium concentration (ppm).
Cr_ppm	Chromium concentration (ppm). Note: Cr determination by ICP-MS may be affected by ArC polyatomic interference at mass 52; collision/reaction cell technology is recommended.
Co_ppm	Cobalt concentration (ppm).
Ni_ppm	Nickel concentration (ppm).
Cu_ppm	Copper concentration (ppm).
Zn_ppm	Zinc concentration (ppm).
Ga_ppm	Gallium concentration (ppm). Ga substitutes for Al in clay minerals and is a useful proxy for clay mineral abundance. Values range from approximately 5–40 ppm, correlating positively with Al2O3.
Rb_ppm	Rubidium concentration (ppm).
Sr_ppm	Strontium concentration (ppm).
Y_ppm	Yttrium concentration (ppm).
Zr_ppm	Zirconium concentration (ppm). Note: Zr may be underreported if zircon grains are not fully dissolved by the chosen digestion method.
Nb_ppm	Niobium concentration (ppm).
Mo_ppm	Molybdenum concentration (ppm). Mo is a redox-sensitive element ranging from approximately 0.1–8 ppm, with enrichment in organic-rich and reducing environments.
Cs_ppm	Caesium concentration (ppm).
Hf_ppm	Hafnium concentration (ppm). Hf co-varies with Zr (Zr/Hf ratio approximately 33–40 in most geological materials) and is a robust provenance indicator. Range: 1–8 ppm.
 
14. Sheet 12: Principal Component Analysis (PCA) Scores
14.1 Sheet Overview
This sheet contains Principal Component Analysis scores and cluster assignments for 5,000 samples. PCA is the standard dimensionality reduction technique in ceramic provenance studies, reducing the multi-element compositional space (typically 20–33 elements) to a small number of orthogonal principal components that capture the maximum variance in the dataset. The first two principal components typically explain 55–70% of the total variance and are plotted as bivariate scatter plots to visualise compositional groupings. The PCA scores in this dataset are generated with realistic cluster offsets calibrated to each clay deposit type, simulating the spatial separation that characterises well-resolved provenance groups in actual Levantine archaeometric studies.
Sheet Name in Workbook: PCA_Scores
Total Records: 5,000 rows
Total Columns: 18

14.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format PCA-XXXXX.
Site_Code	Three-letter site abbreviation.
Clay_Type	Geochemical clay deposit classification.
Region	Physiographic region of origin.
Period	Archaeological period code.
N_Elements_Used	Number of chemical elements included in the PCA computation. Standard practice in ceramic provenance uses 20–33 elements, typically the full NAA suite or equivalent ICP-MS/XRF data.
Transform	Data transformation applied prior to PCA computation. The standard approach for compositional data is log10 transformation (base-10 logarithm of concentrations), which normalises skewed distributions and equalises the influence of elements measured at different concentration scales.
PC1_Score	Score on the first principal component (PC1), which typically explains 40–55% of total variance and separates mafic (basaltic, high positive scores) from felsic/calcareous (negative scores) source signatures. PC1 is dominated by loadings from Fe2O3, TiO2, V, Cr, Co, and Ni (positive) versus SiO2 (negative).
PC2_Score	Score on the second principal component (PC2), typically explaining 12–18% of total variance. PC2 separates calcareous (high CaO, Sr; negative scores) from silicate-dominated (high K2O, Rb; positive scores) compositions.
PC3_Score	Score on the third principal component (PC3), typically explaining 7–12% of total variance and dominated by REE and accessory mineral signatures (La, Ce, Th, U, Nb).
PC4_Score	Score on the fourth principal component (PC4), typically explaining 4–7% of variance, often reflecting chalcophile element (Zn, Cu, As) variation or anthropogenic contamination signals.
PC5_Score	Score on the fifth principal component (PC5), typically explaining 3–5% of variance, often associated with secondary phosphate/manganese enrichment (P2O5, MnO).
PC1_Var_%	Percentage of total variance explained by PC1 for the specific analysis run.
PC2_Var_%	Percentage of total variance explained by PC2.
PC3_Var_%	Percentage of total variance explained by PC3.
Cumul_Var_5PC_%	Cumulative percentage of total variance explained by the first five principal components combined. Values typically range from 72–95%, with higher values indicating more effective dimensionality reduction.
Assigned_Cluster	Cluster identification code (CL-1 through CL-8) assigned through hierarchical cluster analysis (Ward's method) or k-means clustering applied to the PCA score matrix. Clusters correspond to compositional reference groups.
Silhouette_Coeff	Silhouette coefficient for the individual sample's cluster assignment, ranging from −1 to +1. Values above 0.5 indicate strong cluster membership, values of 0.25–0.50 indicate moderate membership, and values below 0.25 or negative indicate weak or incorrect assignment.
 
15. Sheet 13: Discriminant Function Analysis (DFA) Classification
15.1 Sheet Overview
This sheet presents Discriminant Function Analysis results and group classification probabilities for 5,000 samples. DFA is the primary supervised classification technique in ceramic provenance studies, maximising the separation between predefined compositional reference groups. Unlike PCA (unsupervised), DFA uses known group assignments to compute linear functions that optimally discriminate among groups. The classification includes Mahalanobis distance metrics, group membership probabilities, and Wilks' Lambda statistics quantifying overall discriminatory power. The dataset simulates 8 compositional reference groups typical of a comprehensive Southern Levantine provenance study.
Sheet Name in Workbook: DFA_Classification
Total Records: 5,000 rows
Total Columns: 17

15.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format DFA-XXXXX.
Site_Code	Three-letter site abbreviation.
Clay_Type	Geochemical clay deposit classification.
Region	Physiographic region of origin.
Period	Archaeological period code.
DF1_Score	Score on the first discriminant function (DF1), which maximises the ratio of between-group to within-group variance and typically accounts for 70–97% of the discriminatory power.
DF2_Score	Score on the second discriminant function (DF2), orthogonal to DF1.
DF3_Score	Score on the third discriminant function (DF3).
Assigned_Group	Compositional reference group to which the sample is classified with highest posterior probability (GRP-1 through GRP-8).
Group_Probability	Posterior probability of membership in the assigned group, ranging from 0.30 to 1.00. Higher probabilities indicate more confident group assignment. The standard threshold for secure assignment is typically p > 0.05 using the Mahalanobis distance criterion.
Second_Best_Group	Compositional reference group with the second-highest posterior probability, useful for identifying ambiguous assignments and potential group overlap.
Second_Probability	Posterior probability of membership in the second-best group.
Mahalanobis_D2	Squared Mahalanobis distance from the sample to the centroid of its assigned group. D2 accounts for inter-variable correlations and group covariance structure. Within-group D2 values typically range from 1–6 for well-defined groups, with values above the chi-squared critical threshold (approximately 18.3 for 10 variables at α = 0.05) indicating potential outliers.
Within_Group_D2	Squared Mahalanobis distance calculated using only the within-group covariance matrix, providing a measure of how centrally located the sample is within its assigned group.
Wilks_Lambda	Wilks' Lambda statistic for the overall discriminant model, ranging from 0 (perfect discrimination) to 1 (no discrimination). Well-separated reference groups produce values of 0.01–0.05, while overlapping groups yield values of 0.1–0.3.
Classification	Classification accuracy flag: Correct (sample assigned to its known group) or Misclassified (sample assigned to an incorrect group). Overall classification accuracy in well-resolved Levantine provenance studies is typically 85–98%.
N_Variables	Number of chemical variables used in the discriminant functions.
 
16. Sheet 14: Site Catchment and Resource Territory Analysis
16.1 Sheet Overview
This sheet records spatial and logistical parameters for 5,000 records relating to the clay procurement territories of Neolithic sites. The data are structured around Dean Arnold's ethnographic threshold model, which demonstrates that approximately 85% of traditional potters procure clay within 7 km of their production site. The sheet integrates GIS-derived cost-surface analysis with archaeological site catchment parameters, enabling spatial modelling of resource territory extent, overlap, and competition. Parameters include distances to clay, temper, and water sources; walking time estimates based on terrain cost surfaces; and Arnold zone classifications for each procurement relationship.
Sheet Name in Workbook: Site_Catchment
Total Records: 5,000 rows
Total Columns: 19

16.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format SCA-XXXXX for Site Catchment Analysis.
Site_Name	Full archaeological site name.
Site_Code	Three-letter site abbreviation.
Region	Physiographic region of origin.
Period	Archaeological period code.
Latitude	Latitude of the site/sampling point in decimal degrees (WGS84).
Longitude	Longitude of the site/sampling point in decimal degrees (WGS84).
Elevation_m	Elevation of the site above (or below) mean sea level in metres. Jordan Valley sites exhibit negative elevations (to –380 m near the Dead Sea).
Clay_Source_Dist_km	Straight-line distance from the archaeological site to the identified clay source in kilometres. Distribution is log-normal with a mode around 2 km, reflecting the concentration of procurement within Arnold's preferred and typical zones.
Temper_Source_Dist_km	Distance from the site to the nearest source of tempering material in kilometres. Temper procurement distances are generally shorter than clay procurement distances because suitable rock outcrops are often more abundant than workable clay deposits.
Water_Source_Dist_km	Distance from the site to the nearest perennial water source in kilometres. Water proximity is essential for both clay preparation (slaking, levigation) and general site location in the semi-arid Southern Levantine environment.
Walking_Time_min	Estimated one-way walking time from the site to the clay source in minutes, calculated using a GIS cost-surface model incorporating slope gradient and terrain roughness. Values are calculated as approximately 15 minutes per kilometre on flat terrain with adjustments for slope.
Cost_Surface_Value	Cumulative cost-surface value from the site to the clay source, derived from an anisotropic least-cost path analysis using a digital elevation model. Higher values indicate greater terrain difficulty and energy expenditure.
Catchment_Area_km2	Total area of the site catchment zone in square kilometres, calculated for standard radii of 1 km (3.14 km2), 2 km (12.57 km2), 5 km (78.54 km2), or 10 km (314.16 km2).
N_Clay_Sources_5km	Number of distinct clay sources identified within a 5 km radius of the site. Higher values indicate greater resource diversity and procurement options.
N_Clay_Sources_10km	Number of distinct clay sources identified within a 10 km radius of the site.
Arnold_Zone	Classification of the procurement distance according to Arnold's ethnoarchaeological threshold model: Preferred (<1 km), Typical (1–4 km), Threshold (4–7 km), or Non-local (>7 km).
Terrain_Type	Dominant terrain morphology between the site and the clay source. Categories include Flat alluvial, Gentle slope, Moderate slope, Steep wadi, Plateau, and Valley floor.
Slope_Degrees	Average terrain slope along the path from the site to the clay source, measured in degrees. Higher slopes increase travel time and energy cost.
 
17. Sheet 15: Production Organisation and Craft Economy
17.1 Sheet Overview
This sheet compiles 5,000 records documenting the organisational parameters of ceramic production at Neolithic Southern Levantine communities. The data address the fundamental question of whether pottery production was organised at the household, community, or specialist level during the Pottery Neolithic period. Key indicators include the coefficient of variation of vessel rim diameters (a standardisation metric inversely proportional to specialisation), estimated production volumes, the percentage of locally versus non-locally produced pottery, and the inferred production locus. The evidence overwhelmingly indicates household-level production with minimal specialisation throughout the Neolithic period.
Sheet Name in Workbook: Production_Org
Total Records: 5,000 rows
Total Columns: 20

17.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format PRD-XXXXX for Production Organisation.
Site_Name	Full archaeological site name.
Site_Code	Three-letter site abbreviation.
Period	Archaeological period code.
Region	Physiographic region of origin.
Estimated_Pop	Estimated population of the site during the specified period, based on site area and assumed population density (typically 100–300 persons per hectare for Neolithic settlements). Values range from 30 to 600 individuals.
N_Households	Estimated number of households at the site, calculated from population estimates assuming average household sizes of 4–6 persons.
Vessels_Per_HH_Year	Estimated number of ceramic vessels produced per household per year, derived from ethnographic analogy and vessel breakage rates. Values range from 8–25 vessels per household annually.
Annual_Clay_kg	Estimated annual clay consumption per household in kilograms, calculated from vessel count and average vessel mass. Values range from 20–60 kg, representing a readily obtainable quantity from local sources.
CV_Rim_Diameter_%	Coefficient of variation of vessel rim diameters within the site assemblage, expressed as a percentage. High CV values (25–58%) indicate low standardisation characteristic of household production, while low CV values (less than 15%) would indicate specialised production with standardised output.
Standardization_Index	Composite standardisation index (0–1 scale) derived from multiple morphometric variables including rim diameter, wall thickness, and vessel height. Values closer to 0 indicate low standardisation (household production); values closer to 1 indicate high standardisation (specialised production).
Pct_Local_Production	Percentage of the ceramic assemblage identified as locally produced based on petrographic and geochemical provenance analysis. Neolithic assemblages typically show greater than 90% local production.
Pct_Non_Local	Percentage of the ceramic assemblage identified as non-locally produced (imported through exchange). Values are typically less than 5–10% during the Pottery Neolithic.
Firing_Events_Year	Estimated number of firing events conducted per year at the site. Seasonal constraints (dry season preference) limit firing opportunities to approximately 2–8 events per year.
Vessels_Per_Firing	Estimated number of vessels fired simultaneously per firing event. Open-pit/bonfire firings can accommodate 5–25 vessels depending on fire size and vessel dimensions.
Production_Season	Inferred seasonal timing of pottery production: Spring, Summer, Spring-Summer, Spring-Autumn, or Year-round. Mediterranean climate constraints favour production during the dry months (April–September).
Specialization_Level	Inferred level of craft specialisation: Household (all families produce their own pottery), Household+ (some households produce small surpluses), Part-time specialist (individuals known for pottery skill produce for wider community), or Community specialist (dedicated potter serving entire community). Neolithic assemblages overwhelmingly indicate Household or Household+ levels.
Kiln_Type	Type of firing installation documented at the site: Open pit, Bonfire, Simple updraft, or None documented. No specialised kilns are known from the Pottery Neolithic of the Southern Levant.
Est_Firing_Temp_C	Estimated average firing temperature in degrees Celsius for the site assemblage.
Production_Locus	Inferred spatial location of pottery production activities within the settlement: Domestic courtyard, Open area, Designated quarter, or Unknown.
 
18. Sheet 16: Provenance Assignment and Source Attribution
18.1 Sheet Overview
This sheet presents the integrated provenance determinations for 5,000 ceramic samples, synthesising evidence from geochemical analysis, petrographic examination, and multivariate statistical classification. Each record represents the final provenance attribution for an individual sherd, including the assigned clay source type, parent geological formation, procurement distance, confidence level, and the analytical methods supporting the determination. The sheet also records whether the sample is classified as locally produced or exchanged, and the inferred exchange network context where applicable. This integration of multiple independent analytical lines of evidence is the standard practice in modern Levantine ceramic provenance research.
Sheet Name in Workbook: Provenance_Assign
Total Records: 5,000 rows
Total Columns: 18

18.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format PRV-XXXXX for Provenance assignment.
Site_Code	Three-letter site abbreviation.
Region	Physiographic region of origin.
Period	Archaeological period code.
Vessel_Type	Morphological vessel form classification.
Assigned_Clay_Source	Geochemical clay source type assigned through the integrated provenance determination process.
Source_Formation	Specific geological formation identified as the source of the clay raw material.
Source_Distance_km	Estimated distance from the archaeological site to the assigned clay source in kilometres.
Confidence_Level	Qualitative assessment of the reliability of the provenance assignment: High (consistent results across multiple analytical methods), Moderate (generally consistent with minor ambiguities), or Low (significant uncertainty or conflicting indicators).
Method_Primary	Primary analytical method supporting the provenance determination.
Method_Secondary	Secondary analytical method providing corroborating evidence.
DFA_Group	Compositional reference group assigned by Discriminant Function Analysis (GRP-1 through GRP-8).
DFA_Probability	Posterior probability of DFA group membership.
PCA_Cluster	Cluster assignment from Principal Component Analysis and hierarchical clustering (CL-1 through CL-8).
Mahalanobis_D2	Squared Mahalanobis distance to the assigned group centroid.
Local_vs_NonLocal	Binary classification: Local (clay source within 7 km of the archaeological site, consistent with Arnold's procurement threshold) or Non-local (clay source beyond 7 km, implying exchange or unusually distant procurement).
Exchange_Network	Characterisation of the exchange context for non-local ceramics: None (locally produced), Intra-regional (exchange within the same physiographic region), Inter-regional (exchange between different regions), or Unknown.
Notes	Free-text field containing analytical observations, caveats, or interpretive comments relevant to the specific provenance determination.
 
19. Sheet 17: Firing Temperature Estimation
19.1 Sheet Overview
This sheet documents firing temperature estimates for 5,000 ceramic samples, derived from multiple independent analytical indicators. Firing temperature is a critical parameter for understanding Neolithic pyrotechnological capability and its relationship to clay source selection. The dataset records both point estimates and ranges, along with the specific estimation method employed. Mineral transformation indicators (calcite decomposition at approximately 700°C, illite destruction at approximately 850°C, quartz inversion at 573°C, gehlenite neoformation above 800°C) are recorded as binary fields, providing an internal consistency check against the temperature estimate. Vitrification degree, core/margin coloration, and Mohs hardness provide additional corroborating evidence.
Sheet Name in Workbook: Firing_Temp_Est
Total Records: 5,000 rows
Total Columns: 19

19.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format FTE-XXXXX for Firing Temperature Estimation.
Site_Code	Three-letter site abbreviation.
Period	Archaeological period code.
Vessel_Type	Morphological vessel form classification.
Region	Physiographic region of origin.
Fabric_Group	Petrographic fabric group assignment (FG-1 through FG-8).
Est_Firing_Temp_C	Best-estimate original firing temperature in degrees Celsius, representing the peak temperature reached during the firing event. The majority of Neolithic samples cluster between 500–750°C.
Temp_Range_Low_C	Lower bound of the estimated firing temperature range in degrees Celsius. The range reflects analytical uncertainty inherent in the estimation method.
Temp_Range_High_C	Upper bound of the estimated firing temperature range in degrees Celsius.
Estimation_Method	Analytical technique used to estimate firing temperature: Thermal expansion, XRD phase analysis, Mossbauer spectroscopy, Refiring experiment, SEM vitrification, FTIR, or Ceramic color.
Atmosphere	Inferred firing atmosphere (Oxidizing, Reducing, or Mixed/Incomplete).
Vitrification_Degree	Degree of glassy phase formation observed by SEM: No vitrification (below approximately 750°C), Initial (approximately 750–850°C), Extensive (approximately 850–950°C), or Complete (above approximately 950°C).
Calcite_Decomposition	Binary indicator (Yes/No) of whether calcite temper has undergone thermal decomposition (CaCO3 → CaO + CO2), which occurs above approximately 700°C.
Illite_Preserved	Binary indicator (Yes/No) of whether illite crystal structure is preserved, which is maintained below approximately 850°C.
Quartz_Inversion	Binary indicator (Observed/Not observed) of the alpha-beta quartz inversion at 573°C, detectable through thermal expansion measurements or dilatometry.
Gehlenite_Present	Binary indicator (Yes/No) of gehlenite (Ca2Al2SiO7) neoformation, which occurs above approximately 800°C in calcareous ceramics as a reaction product of calcite decomposition with aluminium silicates.
Core_Color_Munsell	Munsell colour of the sherd cross-section core. Dark cores (10YR 4/1, 2.5Y 5/2) indicate incomplete oxidation, while uniform light colours (5YR 5/6, 7.5YR 6/4) indicate complete oxidation.
Margin_Color_Munsell	Munsell colour of the sherd cross-section margins, which are typically more oxidised than the core due to direct contact with the firing atmosphere.
Hardness_Mohs	Mohs scratch hardness of the ceramic body, determined using standard Mohs hardness picks. Low-fired ceramics (below 700°C) typically exhibit hardness of 2–3.5, while medium-fired ceramics (700–850°C) show hardness of 3.5–5.
 
20. Sheet 18: Grain Size Distribution Analysis
20.1 Sheet Overview
This sheet presents comprehensive particle size distribution data for 5,000 clay deposit samples, analysed by laser diffraction granulometry or sieve-pipette methods. Grain size distribution is a fundamental physical property controlling clay workability, shrinkage behaviour, and firing characteristics. The data include seven particle size fractions (clay through coarse sand), four statistical parameters (mean, sorting, skewness, kurtosis in the Folk and Ward system), three percentile values (D10, D50, D90), and the uniformity coefficient. These parameters enable quantitative comparison of clay texture across deposit types and provide essential input for assessing the suitability of natural clay resources for ceramic production without modification (addition of temper).
Sheet Name in Workbook: Grain_Size_Distrib
Total Records: 5,000 rows
Total Columns: 21

20.2 Column Definitions
The following table provides the complete specification for each column in this sheet, including the column header as it appears in the workbook, and a comprehensive description encompassing data type, expected value range, scientific significance, and interpretive context.

Column Name	Description
Sample_ID	Unique identifier in the format GSD-XXXXX for Grain Size Distribution.
Site_Code	Three-letter site abbreviation.
Clay_Type	Geochemical clay deposit classification.
Region	Physiographic region of origin.
Formation	Parent geological formation.
Depth_cm	Sampling depth below the modern ground surface in centimetres.
Clay_pct	Percentage of particles in the clay fraction (less than 2 micrometres). This is the most important single textural parameter for ceramic suitability, with values of 20–60% considered optimal for hand-built pottery production.
Fine_Silt_pct	Percentage of particles in the fine silt fraction (2–20 micrometres). Fine silt contributes to clay plasticity without the extreme shrinkage behaviour of the clay fraction.
Coarse_Silt_pct	Percentage of particles in the coarse silt fraction (20–63 micrometres). Coarse silt acts as a natural temper, reducing shrinkage and improving drying characteristics.
Very_Fine_Sand_pct	Percentage of particles in the very fine sand fraction (63–125 micrometres).
Fine_Sand_pct	Percentage of particles in the fine sand fraction (125–250 micrometres).
Medium_Sand_pct	Percentage of particles in the medium sand fraction (250–500 micrometres).
Coarse_Sand_pct	Percentage of particles in the coarse sand fraction (500–2000 micrometres).
Mean_Phi	Mean grain size expressed in phi (φ) units using the Folk and Ward (1957) graphical method. Higher phi values correspond to finer sediments (phi 8–10 = clay-dominated; phi 4–6 = silt-dominated).
Sorting_Phi	Standard deviation of the grain size distribution in phi units (Folk and Ward), measuring the spread of particle sizes. Values less than 1.0 indicate well-sorted sediment; values of 1–2 indicate poorly sorted; values greater than 2 indicate very poorly sorted.
Skewness	Skewness of the grain size distribution (Folk and Ward), measuring asymmetry. Positive skewness indicates a fine-tailed distribution (excess fine particles), characteristic of alluvial clays. Negative skewness indicates a coarse tail.
Kurtosis	Kurtosis of the grain size distribution (Folk and Ward), measuring the peakedness. Leptokurtic distributions (kurtosis greater than 1.0) indicate concentration around the mean; platykurtic distributions (less than 1.0) indicate broad, flat distributions.
D10_um	Tenth percentile grain diameter in micrometres: 10% of particles are finer than this value. D10 is sensitive to the fine fraction and influences permeability and capillary behaviour.
D50_um	Median grain diameter (fiftieth percentile) in micrometres. D50 is the standard summary statistic for central tendency of the grain size distribution.
D90_um	Ninetieth percentile grain diameter in micrometres: 90% of particles are finer than this value. D90 characterises the coarse tail of the distribution and reflects the maximum natural grain size.
Uniformity_Coeff	Coefficient of uniformity calculated as D60/D10, where D60 and D10 are the 60th and 10th percentile diameters. Values near 1 indicate very uniform grain size; values greater than 4–6 indicate well-graded (diverse) particle sizes typical of mixed-source alluvial deposits.
 
21. Appendix: Reference Codes
21.1 Period Codes
Code	Period Name	Date Range (cal BCE)
PPNA	Pre-Pottery Neolithic A	9500–8500
EPPNB	Early Pre-Pottery Neolithic B	8500–8000
MPPNB	Middle Pre-Pottery Neolithic B	8000–7500
LPPNB	Late Pre-Pottery Neolithic B	7500–6500
PPNC	Pre-Pottery Neolithic C	6500–6000
YAR	Yarmukian	6400–5800
LOD	Lodian (Jericho IX)	6000–5500
WR	Wadi Rabah	5500–4700
LN	Late Neolithic	5000–4500
GH	Ghassulian (Early Chalcolithic)	4500–3800

21.2 Clay Type Codes
Clay Type	Parent Material	Key Geochemical Signature
Alluvial	Mixed transported sediment	Moderate CaO, mixed trace elements
Residual_Terra_Rossa	Judea Group limestone/dolomite	High Al₂O₃, Fe₂O₃; low CaO
Basaltic_Soil	Neogene–Quaternary basalt	Very high Fe₂O₃, TiO₂, Cr, Ni, V
Coastal_Hamra	Kurkar Fm calcareous sandstone	High SiO₂, moderate CaO
Lisan_Marl	Lisan Fm lacustrine deposit	Extreme CaO (25–45%), high Sr
Rendzina	Chalk/marl substrates	High CaO (15–40%), moderate Al₂O₃

