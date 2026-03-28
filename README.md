DATASET DOCUMENTATION
Trace Element Heterogeneity Within Single Kiln-Load Assemblages at Late Bronze Age Ugarit and Its Confounding Effects on Ceramic Provenance Studies Using Instrumental Neutron Activation Analysis
Comprehensive XLSX File Structure Reference
25 Worksheets | 5,000 Rows Per Sheet | 23-44 Columns Per Sheet
Total: 125,000 Data Records | 33 Elements | 13 Reference Groups
2026
 
1. Introduction and Scope
This document provides a comprehensive technical reference for the accompanying Excel workbook entitled 'Ugarit_INAA_Dataset.xlsx,' which contains a systematically generated dummy dataset modelled upon realistic parameters drawn from published Instrumental Neutron Activation Analysis (INAA) studies of Late Bronze Age ceramics from the Eastern Mediterranean. The workbook comprises 25 individual worksheets, each containing a minimum of 5,000 data rows with 23 to 44 columns, collectively encompassing approximately 125,000 records spanning the complete analytical pipeline from raw gamma-ray spectroscopy through final provenance assignment.
The dataset architecture replicates the structure of genuine archaeometric research conducted at major analytical facilities including the Missouri University Research Reactor (MURR) Archaeometry Laboratory and the Helmholtz-Institut at the University of Bonn. Elemental concentrations, uncertainties, detection limits, statistical outputs, and provenance classifications have been generated using probability distributions parameterised from published reference group means and coefficients of variation for established compositional groups including MYBE (Mycenae/Berbati), TIR (Tiryns), CypH (Cyprus West), CypG (Cyprus East), and multiple local Ugarit production groups.
The following sections describe each worksheet in detail, providing: (a) the analytical purpose and scientific context of the sheet; (b) the number and nature of rows and columns; and (c) a column-by-column description of every data field including its units, typical value ranges, and interpretive significance within the broader provenance framework.
 
2. Sheet 1: Sample_Inventory
Purpose and Scientific Context
This sheet constitutes the master archaeological metadata registry for all 5,000 ceramic specimens analysed in the dataset. Each row represents one individual ceramic sherd or vessel fragment recovered from Late Bronze Age contexts at Ugarit (Ras Shamra), its harbour settlement Minet el-Beida, and the satellite palatial complex at Ras Ibn Hani, as well as comparative material from neighbouring Syrian and Lebanese coastal sites. The sheet provides the essential contextual framework linking analytical chemistry data in subsequent sheets to specific archaeological findspots, stratigraphic positions, typological classifications, and physical attributes of each specimen.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Unique alphanumeric identifier for each ceramic specimen, following the format UGA-INAA-XXXXX where XXXXX is a zero-padded sequential integer. This identifier serves as the primary key linking all sheets in the workbook.
Kiln_Load_ID: Identifier grouping specimens hypothesised to originate from the same kiln firing event, formatted as KLN-XXXX. Multiple samples sharing a Kiln_Load_ID are presumed to have been fired contemporaneously, enabling analysis of intra-kiln compositional variability.
Site_Name: The archaeological site from which the specimen was recovered, including Ras Shamra Acropolis, Ras Shamra Royal Palace, Ras Shamra Ville Sud, Minet el-Beida Harbor, Ras Ibn Hani Palace, Tell Sukas, Tell Tweini, Tell Kazel, Tell Arqa, and Byblos.
Excavation_Area: The specific designated excavation area or trench within the site, such as Area A through Area F, Trench I through Trench III, or sondage designations corresponding to the French excavation grid system.
Stratigraphic_Level: The stratigraphic layer designation from which the specimen was excavated, following the site-specific nomenclature (e.g., Level III-b). This provides chronological ordering through the principle of superposition.
Period: Chronological period assignment based on Courtois (1978) Ugarit phasing system: UR1 (c. 1600-1450 BCE), UR2 (c. 1450-1350 BCE), UR3a (c. 1350-1250 BCE), or UR3b (c. 1250-1185 BCE), corresponding to LB IA through LB IIB in the standard Levantine periodisation.
Ware_Type: Typological classification of the ceramic ware category, encompassing Local Common Ware, Local Fine Ware, Local Cooking Ware, Canaanite Transport Jar, Mycenaean Import, Cypriot Base Ring, Cypriot White Slip, Cypriot Red Lustrous, Aegean-Type Local Imitation, Handmade Burnished Ware, and related categories.
Vessel_Form: Morphological classification of the vessel form from which the sherd derives, including bowls, kraters, stirrup jars, pilgrim flasks, jugs, juglets, amphorae, pithoi, cooking pots, chalices, rhyta, pyxides, alabastra, lentoid flasks, and hydriae.
Fabric_Type: Petrographic classification of the ceramic fabric based on macroscopic and thin-section analysis, describing the dominant non-plastic inclusion suite (e.g., Calcareous Fine, Sand-Tempered, Basalt-Tempered, Talc-Tempered, Grog-Tempered, Mixed Temper, Untempered Fine).
Surface_Color_Munsell: Surface colour of the ceramic specimen recorded using the Munsell Soil Color Chart notation system (e.g., Buff 10YR 7/3, Reddish Yellow 5YR 6/6), providing standardised colorimetric description.
Core_Color: Colour of the ceramic body in cross-section, indicating firing atmosphere and completeness (e.g., Gray, Oxidized Red, Sandwich Red-Gray-Red pattern characteristic of incomplete oxidation).
Sherd_Weight_g: Mass of the ceramic sherd specimen in grams, measured to 0.1 g precision using an analytical balance prior to sub-sampling for INAA analysis.
Max_Dimension_mm: Maximum dimension of the sherd in millimetres, providing a metric of specimen size relevant to sampling representativeness.
Wall_Thickness_mm: Thickness of the vessel wall at the point of sampling, measured in millimetres using digital callipers. This parameter relates to vessel function and production technique.
Temper_Grain_Size_mm: Maximum observed grain size of intentionally added temper inclusions in millimetres, estimated from macroscopic examination or thin-section petrography.
Temper_Volume_Pct: Estimated volumetric percentage of non-plastic temper inclusions in the ceramic body, determined by point-counting or visual estimation from petrographic thin sections.
Firing_Atmosphere: Inferred atmospheric conditions during kiln firing: Oxidizing (O2-rich), Reducing (O2-poor), Mixed/Variable, or specific sequential combinations (e.g., Oxidizing-Reducing-Oxidizing sandwich firing).
Estimated_Firing_Temp_C: Estimated peak firing temperature in degrees Celsius, inferred from mineral phase assemblages, vitrification state, and refiring experiments. Range typically 650-1150 degrees C for LBA Levantine ceramics.
Compositional_Group: INAA-derived compositional group assignment based on multivariate statistical analysis. Groups include UGA-Local-A, UGA-Local-B, UGA-Local-C, UGA-Cooking, MYBE, TIR, CypH, CypG, Outlier, and Unassigned.
Provenance_Assignment: Interpreted geographic provenance based on the totality of evidence (INAA group, petrography, typology): Local Ugarit, Argolid (Greece), Tiryns Region, Cyprus West, Cyprus East, Northern Levant, Southern Levant, Unassigned, Ambiguous, or Outlier.
Excavation_Year: Calendar year in which the specimen was excavated, ranging from 1929 (earliest French excavations under C.F.A. Schaeffer) through 2024 (recent Syrian-international campaigns).
Catalogue_Number: Museum or excavation catalogue number in the format RS-XX-XXXX, where RS denotes Ras Shamra and the subsequent digits indicate excavation season and sequential find number.
MURR_Lab_Number: Laboratory accession number assigned by the Missouri University Research Reactor Archaeometry Laboratory upon receipt of the sample for INAA analysis.
Analyst_Initials: Initials of the analyst who performed the INAA measurement, providing traceability to individual laboratory personnel for quality assurance purposes.
Analysis_Date: Calendar date on which the INAA measurement was completed, formatted as YYYY-MM-DD in ISO 8601 standard.
 
3. Sheet 2: Short_Irradiation_Raw
Purpose and Scientific Context
This sheet records the raw gamma-ray spectroscopic count data obtained during the short-irradiation sequence of the INAA protocol. In the standard MURR procedure, samples are subjected to a 5-second irradiation at a thermal neutron flux of approximately 8 x 10^13 n cm^-2 s^-1, followed by a 25-minute decay period and a 720-second live-time count on a high-purity germanium (HPGe) detector. The raw counts for nine short-lived activation products are recorded alongside essential spectroscopic metadata including dead time, live time, detector identification, and geometric positioning parameters necessary for quantitative concentration calculations.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key linking to the Sample_Inventory sheet.
Irradiation_Batch: Batch identifier for the short irradiation run, formatted as SIR-XXX. Samples irradiated in the same batch experience identical neutron flux conditions, enabling batch-level quality control.
Irradiation_Duration_s: Duration of the short irradiation in seconds (standard: 5 seconds at MURR). This parameter directly affects the induced radioactivity and resultant count rates.
Neutron_Flux_n_cm2_s: Thermal neutron flux in neutrons per square centimetre per second at the irradiation position, expressed in scientific notation. Typical MURR values range from 7.5 x 10^13 to 8.5 x 10^13.
Decay_Time_s: Time elapsed between end of irradiation and beginning of gamma-ray counting, in seconds. Standard MURR protocol specifies approximately 1500 seconds (25 minutes) to allow very short-lived activities to decay.
Count_Duration_s: Preset counting time for gamma-ray spectral acquisition in seconds (standard: 720 seconds for short irradiation products).
Na24_Counts: Integrated net peak area counts for the 1369 keV gamma-ray line of Na-24 (half-life 14.96 hours), used for sodium determination.
Al28_Counts: Integrated net peak area counts for the 1779 keV gamma-ray line of Al-28 (half-life 2.24 minutes), used for aluminium determination.
K42_Counts: Integrated net peak area counts for the 1525 keV gamma-ray line of K-42 (half-life 12.36 hours), used for potassium determination.
Ca49_Counts: Integrated net peak area counts for the 3084 keV gamma-ray line of Ca-49 (half-life 8.72 minutes), used for calcium determination.
Ti51_Counts: Integrated net peak area counts for the 320 keV gamma-ray line of Ti-51 (half-life 5.76 minutes), used for titanium determination.
V52_Counts: Integrated net peak area counts for the 1434 keV gamma-ray line of V-52 (half-life 3.74 minutes), used for vanadium determination.
Mn56_Counts: Integrated net peak area counts for the 847 keV gamma-ray line of Mn-56 (half-life 2.58 hours), used for manganese determination.
Ba139_Counts: Integrated net peak area counts for the 166 keV gamma-ray line of Ba-139 (half-life 83.06 minutes), used for barium determination.
Dy165_Counts: Integrated net peak area counts for the 95 keV gamma-ray line of Dy-165 (half-life 2.33 hours), used for dysprosium determination.
Dead_Time_Pct: Percentage of the counting interval during which the detector electronics were unable to process incoming events due to pulse pile-up. Values exceeding 10% indicate potential spectral distortion.
Live_Time_s: Actual live (active) counting time in seconds, equal to the preset count duration minus dead-time losses. Used in the denominator of count-rate calculations.
Sample_Mass_mg: Mass of the powdered sample aliquot in milligrams, typically 140-220 mg, measured to 0.1 mg precision on an analytical microbalance.
Vial_Type: Type of irradiation container used: Polyethylene for short irradiation, high-purity quartz for long irradiation. Material purity is critical to minimise blank contributions.
Detector_ID: Unique identifier of the HPGe detector used for gamma-ray spectroscopy (e.g., HPGe-1 through HPGe-4), enabling detector-specific efficiency calibration corrections.
Geometry_Position: Shelf position (1-5) relative to the detector face during counting. Position 1 is closest to the detector, providing highest count rates but greatest geometric sensitivity. Positions 4-5 reduce dead time for highly active samples.
Spectrum_File_ID: Filename of the raw gamma-ray spectrum data file stored in the laboratory information management system, formatted as SXXXXX_short.spc.
Background_Subtracted: Binary flag indicating whether ambient background radiation has been subtracted from the gross peak areas to yield net counts (Yes/No).
QC_Flag: Quality control status flag: Pass indicates all spectral parameters within acceptable limits; Flag indicates one or more anomalies requiring review (elevated dead time, low count rates, spectral artifacts).
Notes: Free-text field for analyst observations regarding sample condition, measurement anomalies, or procedural deviations (e.g., slight moisture noted, irregular geometry, replicate sample).
 
4. Sheet 3: Short_Irrad_Conc
Purpose and Scientific Context
This sheet presents the elemental concentrations derived from the short irradiation gamma-ray spectra for nine elements (Na, Al, K, Ca, Ti, V, Mn, Ba, Dy). Concentrations are calculated from raw count data using the comparator method against certified reference materials, with corrections applied for neutron flux variations, decay during counting, detector efficiency, gamma-ray self-absorption, and sample mass. Each concentration value is accompanied by its associated analytical uncertainty, propagated from counting statistics, calibration uncertainties, and mass measurement errors.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key linking to the Sample_Inventory sheet.
Na_pct / Na_Uncertainty_pct: Sodium concentration and associated 1-sigma uncertainty, both expressed as weight percent (wt%). Typical range for Levantine ceramics: 0.3-2.0%. Na is a large-ion lithophile element susceptible to post-depositional leaching.
Al_pct / Al_Uncertainty_pct: Aluminium concentration and uncertainty in wt%. Range: 5-10%. Al reflects the clay mineral content and is relatively immobile during burial.
K_pct / K_Uncertainty_pct: Potassium concentration and uncertainty in wt%. Range: 1-4%. K is associated with illite and feldspar phases; subject to moderate post-depositional mobility.
Ca_pct / Ca_Uncertainty_pct: Calcium concentration and uncertainty in wt%. Range: 1-20%. Highly variable due to both primary carbonate content in calcareous clays and secondary calcite precipitation during burial.
Ti_pct / Ti_Uncertainty_pct: Titanium concentration and uncertainty in wt%. Range: 0.3-0.6%. Ti resides in detrital heavy minerals (rutile, ilmenite) and is highly immobile, making it a reliable provenance indicator.
V_ppm / V_Uncertainty_ppm: Vanadium concentration and uncertainty in parts per million. Range: 50-200 ppm. V substitutes in clay minerals and iron oxides.
Mn_ppm / Mn_Uncertainty_ppm: Manganese concentration and uncertainty in ppm. Range: 500-1500 ppm. Subject to biogenic enrichment through manganese oxide precipitation in burial environments.
Ba_ppm / Ba_Uncertainty_ppm: Barium concentration and uncertainty in ppm. Range: 200-700 ppm. Ba substitutes for K in feldspar and can be enriched by groundwater interaction.
Dy_ppm / Dy_Uncertainty_ppm: Dysprosium concentration and uncertainty in ppm. Range: 3-6 ppm. Dy is a heavy rare earth element, highly immobile and valuable for provenance discrimination.
Normalization_Factor: Multiplicative correction factor applied to account for neutron flux variation within the irradiation batch, calculated from co-irradiated flux monitors. Values near 1.00 indicate uniform flux exposure.
Batch_ID: Short irradiation batch identifier linking to the irradiation parameters in Sheet 2.
Standard_Used: Certified reference material used as the primary calibration standard for concentration calculations (typically SRM-1633b coal fly ash from NIST).
QC_Status: Quality control assessment for the concentration determinations: Pass or Flag.
 
5. Sheet 4: Mid_Count_Conc
Purpose and Scientific Context
This sheet contains elemental concentrations determined from the mid-count gamma-ray spectra, acquired 7-8 days after the 24-hour long irradiation. The mid-count targets seven elements with activation products having half-lives in the range of 1-11 days (As, La, Sm, U, Nd, Yb, Lu), which includes several critically important rare earth elements. The REE (La, Sm, Nd, Yb, Lu) are among the most reliable provenance discriminators due to their geochemical immobility and systematic inter-element correlations governed by ionic radius.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
As_ppm / As_Unc_ppm: Arsenic concentration and uncertainty in ppm. Range: 5-20 ppm. As is a chalcophile element; concentrations may be affected by volatilisation during high-temperature firing and post-depositional contamination.
La_ppm / La_Unc_ppm: Lanthanum concentration and uncertainty in ppm. Range: 20-45 ppm. La is a light rare earth element, highly immobile, with analytical precision typically 1.5-3% RSD. La is one of the most reliable provenance discriminators.
Sm_ppm / Sm_Unc_ppm: Samarium concentration and uncertainty in ppm. Range: 4-8 ppm. Sm is a middle REE with excellent analytical precision (2% RSD) and high discriminating power.
U_ppm / U_Unc_ppm: Uranium concentration and uncertainty in ppm. Range: 2-5 ppm. U determined via the 228 keV line of Np-239, the daughter product of U-239. Subject to moderate post-depositional mobility in oxidising groundwater environments.
Nd_ppm / Nd_Unc_ppm: Neodymium concentration and uncertainty in ppm. Range: 20-40 ppm. Nd is a light REE measured via the 91 keV line of Nd-147 (half-life 10.98 days).
Yb_ppm / Yb_Unc_ppm: Ytterbium concentration and uncertainty in ppm. Range: 2-4 ppm. Yb is a heavy REE, providing the HREE complement to La and Ce for calculating REE fractionation ratios (La/Yb).
Lu_ppm / Lu_Unc_ppm: Lutetium concentration and uncertainty in ppm. Range: 0.3-0.6 ppm. Lu is the heaviest naturally occurring REE, anchoring the heavy end of chondrite-normalised REE patterns.
Decay_Days: Number of days elapsed between end of long irradiation and commencement of mid-count spectral acquisition. Standard: 7-8.5 days.
Count_Duration_s: Preset counting time for mid-count spectral acquisition in seconds (standard: 2000 seconds).
Irrad_Batch: Long irradiation batch identifier, formatted as LIR-XXX.
Detector_ID: HPGe detector identifier used for the mid-count measurement.
Geometry: Shelf position during mid-count measurement.
Spectrum_File: Filename of the mid-count gamma-ray spectrum stored as SXXXXX_mid.spc.
Standard_Ref: Reference standard used for calibration.
QC_Status: Quality control flag for mid-count determinations.
 
6. Sheet 5: Long_Count_Conc
Purpose and Scientific Context
This sheet presents concentration data for seventeen elements determined from the long-count gamma-ray spectra, acquired 4-5 weeks after the 24-hour irradiation with a 10,800-second (3-hour) counting time. These elements include the backbone of ceramic provenance analysis: Sc, Cr, Fe, Co, the critical REE pair Ce-Eu, and the high-field-strength elements Hf, Ta, and Th. The extended decay period and long counting time provide exceptional sensitivity for long-lived activation products, achieving analytical precision of 1-4% RSD for most elements. Each concentration is paired with its propagated uncertainty.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
Sc_ppm / Sc_ppm_Unc: Scandium concentration and uncertainty in ppm. Range: 10-25 ppm. Sc (via Sc-46, half-life 83.79 days, 889 keV) is one of the most precisely measured and provenance-diagnostic elements in ceramic INAA, with typical RSD of 1.5%.
Cr_ppm / Cr_ppm_Unc: Chromium concentration and uncertainty in ppm. Range: 50-200 ppm. Cr is associated with chromite and clay minerals. Elevated Cr distinguishes Cypriot (ophiolite-influenced) clays from Argolid sources.
Fe_pct / Fe_pct_Unc: Iron concentration and uncertainty in wt%. Range: 3-8%. Fe is a major element reflecting clay mineralogy and iron oxide content. Calcareous Levantine clays are characteristically iron-poor (2-3.5%) relative to Aegean clays (5-6%).
Co_ppm / Co_ppm_Unc: Cobalt concentration and uncertainty in ppm. Range: 10-30 ppm. Co is geochemically coherent with Fe and provides useful discrimination between compositional groups.
Ni_ppm / Ni_ppm_Unc: Nickel concentration and uncertainty in ppm. Range: 90-550 ppm. Ni is associated with mafic/ultramafic geological sources and shows elevated concentrations in Cypriot ceramics from ophiolite-derived clay sources.
Zn_ppm / Zn_ppm_Unc: Zinc concentration and uncertainty in ppm. Range: 80-130 ppm. Zn is a moderately useful provenance discriminator with RSD typically 4-8%.
Rb_ppm / Rb_ppm_Unc: Rubidium concentration and uncertainty in ppm. Range: 50-170 ppm. Rb is a large-ion lithophile element geochemically coherent with K; subject to post-depositional leaching similar to Na and Cs.
Sr_ppm / Sr_ppm_Unc: Strontium concentration and uncertainty in ppm. Range: 100-500 ppm. Sr substitutes for Ca in carbonates and plagioclase; its concentration correlates with Ca content and is influenced by temper additions and post-depositional alteration.
Zr_ppm / Zr_ppm_Unc: Zirconium concentration and uncertainty in ppm. Range: 50-230 ppm. Zr resides in detrital zircon and is highly immobile, making it a reliable provenance indicator despite moderate analytical precision.
Sb_ppm / Sb_ppm_Unc: Antimony concentration and uncertainty in ppm. Range: 0.5-2.5 ppm. Sb is a volatile chalcophile element; some specimens may show firing-related depletion.
Cs_ppm / Cs_ppm_Unc: Caesium concentration and uncertainty in ppm. Range: 2-15 ppm. Cs is highly susceptible to post-depositional leaching and is frequently excluded from provenance analysis in waterlogged or coastal burial environments.
Ce_ppm / Ce_ppm_Unc: Cerium concentration and uncertainty in ppm. Range: 30-100 ppm. Ce is a light REE with excellent analytical precision (2% RSD); the Ce/La ratio may reveal Ce anomalies related to redox conditions.
Eu_ppm / Eu_ppm_Unc: Europium concentration and uncertainty in ppm. Range: 0.8-1.4 ppm. Eu is a middle REE measured via the long-lived Eu-152 (half-life 13.54 years); the Eu anomaly (Eu/Eu*) reflects feldspar fractionation.
Tb_ppm / Tb_ppm_Unc: Terbium concentration and uncertainty in ppm. Range: 0.5-1.0 ppm. Tb is a middle-to-heavy REE providing additional discrimination in the REE pattern.
Hf_ppm / Hf_ppm_Unc: Hafnium concentration and uncertainty in ppm. Range: 2.5-5.0 ppm. Hf is geochemically coherent with Zr (both HFSE) and resides in detrital zircon; highly immobile and diagnostic.
Ta_ppm / Ta_ppm_Unc: Tantalum concentration and uncertainty in ppm. Range: 0.4-1.3 ppm. Ta is a high-field-strength element associated with resistate heavy minerals; highly immobile.
Th_ppm / Th_ppm_Unc: Thorium concentration and uncertainty in ppm. Range: 5-20 ppm. Th is an actinide element with exceptional provenance utility (RSD 1.5-3%), residing in monazite and other resistate phases. The Th/Sc ratio effectively discriminates local Levantine (0.4-0.6) from Aegean (0.5-0.55) productions.
Decay_Weeks: Weeks elapsed between end of long irradiation and commencement of long-count. Standard: 4-5.5 weeks.
Count_Duration_s: Counting time for long-count spectra (standard: 10,800 seconds = 3 hours).
Batch: Long irradiation batch identifier.
QC: Quality control flag for long-count determinations.
 
7. Sheet 6: Combined_Conc_Matrix
Purpose and Scientific Context
This sheet consolidates all 33 elemental concentrations from the three counting sequences into a single comprehensive matrix, alongside derived geochemical ratios and indices. This unified dataset serves as the primary input for all multivariate statistical analyses. Each row corresponds to one specimen with its full chemical fingerprint, compositional group assignment, and kiln-load affiliation.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
Compositional_Group: INAA compositional group assignment derived from multivariate statistical analysis.
Kiln_Load_ID: Kiln-load affiliation for intra-kiln variability studies.
[33 Element Columns]: Complete set of 33 elemental concentrations: Na%, Al%, K%, Ca%, Ti%, V ppm, Mn ppm, Ba ppm, Dy ppm, As ppm, La ppm, Sm ppm, U ppm, Nd ppm, Yb ppm, Lu ppm, Sc ppm, Cr ppm, Fe%, Co ppm, Ni ppm, Zn ppm, Rb ppm, Sr ppm, Zr ppm, Sb ppm, Cs ppm, Ce ppm, Eu ppm, Tb ppm, Hf ppm, Ta ppm, Th ppm.
Total_REE_ppm: Sum of all determined rare earth elements (La+Ce+Nd+Sm+Eu+Tb+Dy+Yb+Lu) in ppm. Provides a bulk REE abundance metric.
La_Yb_Ratio: Ratio of La to Yb concentrations, a standard measure of light-to-heavy REE fractionation. Higher values indicate LREE enrichment characteristic of specific clay mineralogies.
Eu_Anomaly: Europium anomaly calculated as Eu/(Sm x Tb)^0.5, quantifying the deviation of Eu from the smooth REE pattern. Values less than 1.0 indicate negative Eu anomaly (feldspar removal from source).
Th_Sc_Ratio: Ratio of Th to Sc, effective for discriminating felsic (high Th/Sc) from mafic (low Th/Sc) source contributions. Local Ugarit ceramics typically show Th/Sc of 0.4-0.6 versus Aegean values of 0.5-0.55.
Cr_Sc_Ratio: Ratio of Cr to Sc, useful for identifying ophiolite-influenced clay sources. Elevated Cr/Sc (>15) is diagnostic of Cypriot productions derived from Troodos ophiolite-derived sediments.
 
8. Sheet 7: Measurement_Uncertainties
Purpose and Scientific Context
This sheet provides the complete uncertainty budget for every elemental determination across all 5,000 specimens. Both absolute uncertainties (in the same units as the concentration) and relative uncertainties (as percentage of the measured value) are tabulated. Uncertainties are propagated from counting statistics (Poisson uncertainty on net peak areas), calibration curve uncertainties, mass measurement uncertainties, neutron flux monitor uncertainties, and detector efficiency uncertainties. These uncertainty values are essential inputs for Mahalanobis distance calculations and for proper weighting in multivariate statistical procedures.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
[33 Absolute Uncertainty Columns]: One column per element providing the absolute 1-sigma analytical uncertainty in the native concentration units (wt% for major elements, ppm for trace elements). Computed by quadrature propagation of all individual uncertainty components.
[10 Relative Uncertainty Columns]: Relative uncertainties (as percentage of measured value) for the ten most provenance-critical elements: Na%, Ca%, Fe%, Sc, La, Ce, Eu, Th, Hf, and Cr. These relative values facilitate inter-element comparison of measurement quality.
 
9. Sheet 8: Detection_Limit_Flags
Purpose and Scientific Context
This sheet provides element-by-element data quality flags for each specimen, classifying each measurement as Above Detection Limit (ADL), Below Detection Limit (BDL), or Near Detection Limit (NDL). Detection limits are calculated as three times the standard deviation of the background signal in the spectral region of the analytical peak. Specimens with excessive numbers of BDL values may be unsuitable for multivariate provenance analysis due to incomplete chemical characterisation.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
[33 Element Flag Columns]: Detection limit status for each element: ADL (concentration exceeds 3x background, reliable quantitation), BDL (concentration below detection limit, value reported as upper bound), NDL (concentration within 3-10x background, quantitation possible but with elevated uncertainty).
Total_BDL_Count: Total number of elements with concentrations below detection limit for this specimen.
Pct_Elements_Above_DL: Percentage of the 33-element suite with reliable quantitation (ADL status).
Analytical_Quality_Grade: Overall quality grade based on BDL count: A (0 BDL), B (1-2 BDL), C (3-5 BDL), D (6+ BDL).
Usable_For_Provenance: Assessment of whether the specimen provides sufficient elemental coverage for reliable provenance assignment: Yes, Marginal, or No.
 
10. Sheet 9: Log10_Transformed
Purpose and Scientific Context
This sheet contains the base-10 logarithmic transformations of all 33 elemental concentrations. Log-transformation is the standard pre-processing step in ceramic provenance studies (recommended by Glascock 1992 and the MURR protocol) because it normalises the highly right-skewed distributions typical of geochemical data, stabilises variance across elements measured at vastly different concentration scales (percent vs. sub-ppm), and improves the multivariate normality assumption underlying Mahalanobis distance calculations.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
Compositional_Group: Group assignment.
[33 log10 Element Columns]: Base-10 logarithm of each elemental concentration. For elements in wt%, log10(wt%) is computed directly. For elements in ppm, log10(ppm) is used. Values are computed as log10(max(concentration, 1e-6)) to handle any zero or negative values from background subtraction.
Centroid_Distance: Euclidean distance in log10-transformed multivariate space from each specimen to its assigned group centroid. Provides a measure of typicality within the compositional group.
Robust_Distance: Robust Mahalanobis distance computed using minimum covariance determinant (MCD) estimator, less sensitive to outliers than the classical Mahalanobis distance.
 
11. Sheet 10: PCA_Scores
Purpose and Scientific Context
This sheet presents the principal component scores for all specimens projected onto the first ten principal components extracted from the log10-transformed concentration data. PCA reduces the 33-dimensional chemical space to a lower-dimensional representation that captures the maximum variance, enabling visualisation of compositional group structure in two or three dimensions. The variance explained by each component and outlier diagnostics (Hotelling T-squared and Squared Prediction Error) are included.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
Compositional_Group: Assigned group for colour-coding in PCA biplots.
PC1 through PC10: Scores on principal components 1 through 10. PC1 and PC2 typically capture 40-65% of total variance and provide the primary biplot axes for visualising group separation.
PC1_Pct_Var through Cumulative_Var_PC3: Percentage of total variance explained by PC1, PC2, and PC3 individually, and cumulative variance through PC3.
Hotelling_T2: Hotelling T-squared statistic measuring the distance from the multivariate centre in the PC model space. Values exceeding T2_Critical_95 flag potential outliers.
T2_Critical_95: Critical value of the Hotelling T-squared distribution at the 95% confidence level for the given number of components and specimens.
Outlier_Flag_T2: Binary flag (Yes/No) indicating whether T2 exceeds the critical value.
SPE_Residual: Squared Prediction Error (Q-residual) measuring the portion of a specimen's variance not captured by the retained principal components.
SPE_Critical_95 / Outlier_Flag_SPE: Critical SPE value and binary outlier flag at 95% confidence.
Cluster_Assignment: Cluster number from k-means clustering in PC space.
Silhouette_Score: Silhouette coefficient for each specimen's cluster assignment, ranging from -1 (misclassified) to +1 (well-classified).
Distance_to_Centroid: Euclidean distance to the assigned cluster centroid in PC space.
 
12. Sheet 11: PCA_Loadings
Purpose and Scientific Context
This sheet documents the element loadings on principal components 1 through 8, along with comprehensive analytical metadata for each of the 33 measured elements. Loadings indicate the contribution and direction of each element's influence on each principal component. Elements with high absolute loadings on a given PC are the primary drivers of variance captured by that component. The sheet also provides nuclear parameters, analytical characteristics, and recommendations regarding each element's suitability for provenance studies, sensitivity to post-depositional alteration, and response to temper dilution. For the 5,000-row requirement, the 33 elements are replicated with indexed variants to model measurement replications.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Element: Element name with column identifier (e.g., Na_pct, La_ppm) or replicate designation.
PC1_Loading through PC8_Loading: Loading coefficients on principal components 1 through 8, ranging from -1 to +1. Large positive loadings indicate the element increases in the positive PC direction.
Communality: Proportion of each element's variance explained by the retained components (sum of squared loadings). Values near 1.0 indicate the element is well-represented by the PC model.
Element_Group: Geochemical classification: Major, Transition, REE, LILE (Large-Ion Lithophile), HFSE (High-Field-Strength), Chalcophile, or Actinide.
Atomic_Number: Atomic number of the element.
Measurement_Count: Counting sequence in which the element is determined: Short, Mid, or Long.
Typical_Detection_Limit: Detection limit in the native units, representing the minimum reliably quantifiable concentration.
Analytical_Precision_Pct: Typical relative standard deviation (RSD in %) for the element under routine analytical conditions.
Recommended_For_Provenance: Assessment of whether the element is recommended for inclusion in multivariate provenance analysis: Yes (reliable), Caution (context-dependent), or No (unreliable).
Post_Dep_Sensitivity: Susceptibility to post-depositional chemical alteration: Low, Medium, or High.
Temper_Sensitivity: Degree to which temper additions affect the element's concentration in the ceramic body: Low, Medium, or High.
Dilution_Correctable: Whether temper dilution effects on this element can be corrected using the Bonn dilution factor method: Yes, Partial, or No.
Geochemical_Behavior: Geochemical affinity classification: LILE, HFSE, Transition, LREE, MREE, HREE, Chalcophile, Actinide, or Major.
Isotope_Used: Specific radioactive isotope measured for the element determination (e.g., Na-24, Sc-46, La-140).
Half_Life_Days: Half-life of the measured radioisotope in days.
Gamma_Energy_keV: Primary gamma-ray energy used for quantification in keV.
Count_Sequence: Whether the element is measured in the Short, Mid, or Long counting sequence.
 
13. Sheet 12: Cluster_Analysis
Purpose and Scientific Context
This sheet presents the results of multiple clustering algorithms applied to the log10-transformed concentration data, enabling comparison of group assignments across different methodological approaches. Algorithms include Ward's hierarchical clustering, k-means with varying k values (8, 10, 12), DBSCAN density-based clustering, and average-linkage agglomerative clustering. Internal validation metrics (silhouette coefficients, Calinski-Harabasz index, Davies-Bouldin index, cophenetic correlation) quantify cluster quality, while comparison with INAA compositional groups assesses agreement between statistical and analyst-derived classifications.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
Ward_Cluster: Cluster assignment from Ward's minimum-variance hierarchical clustering method.
KMeans_Cluster_K8 / K10 / K12: Cluster assignments from k-means clustering with k = 8, 10, and 12 respectively, enabling assessment of sensitivity to the number of clusters.
DBSCAN_Cluster: Cluster assignment from Density-Based Spatial Clustering of Applications with Noise. Value -1 indicates noise points (outliers not assigned to any cluster).
Agglom_Average_Link: Cluster assignment from average-linkage agglomerative hierarchical clustering.
Silhouette_Ward / Silhouette_KMeans8: Silhouette coefficients for Ward and k-means (k=8) assignments per specimen.
Calinski_Harabasz: Calinski-Harabasz index (variance ratio criterion) measuring the ratio of between-cluster to within-cluster dispersion. Higher values indicate better-defined clusters.
Davies_Bouldin: Davies-Bouldin index measuring average similarity between each cluster and its most similar cluster. Lower values indicate better separation.
Cophenetic_Corr: Cophenetic correlation coefficient measuring how faithfully the dendrogram preserves pairwise distances. Values above 0.7 indicate acceptable dendogram fidelity.
Merge_Distance / Merge_Level: Distance and hierarchical level at which the specimen joins its cluster in the dendrogram.
Within_Cluster_SS / Between_Cluster_SS / Total_SS: Within-cluster, between-cluster, and total sums of squares for the specimen's cluster assignment.
Cluster_Size: Number of specimens in the assigned cluster.
Nearest_Cluster / Inter_Cluster_Dist: Identifier and distance to the nearest alternative cluster, indicating potential for misclassification.
Assigned_Comp_Group: INAA compositional group from analyst interpretation.
Agreement_With_INAA: Whether the statistical cluster assignment agrees with the analyst-assigned INAA group: Match, Mismatch, or Ambiguous.
Confidence_Level: Confidence in the cluster assignment: High, Medium, or Low.
Misclass_Risk_Pct: Estimated probability of misclassification based on the specimen's position relative to cluster boundaries.
Notes: Observations regarding clustering anomalies.
 
14. Sheet 13: Mahalanobis_Distances
Purpose and Scientific Context
This sheet contains the squared Mahalanobis distances from each specimen to each of thirteen reference compositional groups, calculated using the log10-transformed concentration data and the pooled within-group covariance matrix. The Mahalanobis distance accounts for inter-element correlations and differential variances, providing a more rigorous measure of multivariate similarity than Euclidean distance. The Bonn modified Mahalanobis distance with dilution factor correction is employed, following the methodology of Beier and Mommsen (1994).
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
True_Group: Known or hypothesised compositional group for validation purposes.
D2_UGA_Local_A through D2_TKaD: Squared Mahalanobis distance to each of 13 reference groups: UGA_Local_A, UGA_Local_B, UGA_Local_C, UGA_Cooking, MYBE, TIR, ACb2, CypH, CypG, CypE, SidA, TKaA, TKaD.
Min_D2 / Min_D2_Group: Smallest squared Mahalanobis distance and the corresponding best-matching reference group.
Second_Min_D2 / Second_Min_Group: Second-smallest distance and corresponding group, enabling assessment of assignment ambiguity.
D2_Ratio: Ratio of second-minimum to minimum D2. Values close to 1.0 indicate ambiguous assignment between two groups; values >3.0 indicate unequivocal assignment.
Dilution_Factor: Best-fit dilution factor (f) estimated from the Bonn modified Mahalanobis procedure, correcting for non-plastic temper dilution of trace elements.
N_Elements_Used: Number of elements included in the Mahalanobis calculation (typically 20-28 after exclusion of unreliable elements).
DF_Numerator / DF_Denominator: Degrees of freedom for the F-distribution used to convert D2 to membership probability.
Chi2_Critical_95 / Chi2_Critical_99: Critical chi-squared values at 95% and 99% confidence levels for the given degrees of freedom.
 
15. Sheet 14: Group_Membership_Prob
Purpose and Scientific Context
This sheet converts the Mahalanobis distances from Sheet 13 into posterior membership probabilities for each reference group, providing the probabilistic framework for provenance assignment. Probabilities are computed assuming multivariate normal distributions within each group and equal prior probabilities across groups. Specimens are assigned to the group with the highest posterior probability, with classification confidence assessed by the ratio of first-to-second highest probabilities. Jackknifed (leave-one-out) cross-validation results validate the robustness of each assignment.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
True_Group: Known compositional group.
P_UGA_Local_A through P_TKaD: Posterior membership probability for each of the 13 reference groups, normalised to sum to 1.0 across all groups.
Max_Prob / Assigned_Group: Highest membership probability and corresponding group assignment.
Second_Prob / Second_Group: Second-highest probability and corresponding group.
Prob_Ratio: Ratio of maximum to second-highest probability. Values >5 indicate high classification confidence.
Classification_Confidence: Qualitative confidence assessment: High (Max_Prob > 0.6), Medium (0.3-0.6), or Low (<0.3).
Jackknifed_Class: Group assignment from jackknifed (leave-one-out) cross-validation, testing whether the specimen classifies consistently when removed from its reference group.
Jackknife_Match: Whether the jackknifed classification matches the full-dataset classification: Yes or No.
Cross_Val_Prob: Posterior probability from the jackknifed classification.
Posterior_Prob: Posterior probability computed using Bayesian methods with archaeological prior information.
Prior_Prob: Equal prior probability (1/number of groups) used in the baseline classification.
 
16. Sheet 15: MYBE_Reference_Group
Purpose and Scientific Context
This sheet provides the complete INAA concentration data for 5,000 specimens assigned to the MYBE (Mycenae/Berbati) reference group, the most extensively characterised compositional group in Aegean archaeometry. The MYBE group encompasses ceramics produced in the northeastern Peloponnese, primarily in the Argolid region around Mycenae and the Berbati Valley. This reference dataset, compiled from analyses at the Bonn and MURR laboratories, serves as the primary benchmark against which potential Mycenaean imports at Ugarit are evaluated.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Unique identifier within the MYBE reference dataset.
Site_Origin: Archaeological site from which the reference specimen was recovered: Mycenae, Berbati, Tiryns, Midea, Asine, Dendra, Prosymna, Argos, Nauplion, or Lerna.
Vessel_Type: Morphological classification of the vessel form.
LH_Phase: Late Helladic ceramic phase: LH IIIA1, LH IIIA2 Early, LH IIIA2 Late, LH IIIB1, LH IIIB2, or LH IIIC Early.
[21 Element Columns]: Concentrations for 21 key elements: Na%, Al%, K%, Ca%, Ti%, V ppm, Mn ppm, Ba ppm, Dy ppm, La ppm, Sm ppm, Ce ppm, Eu ppm, Sc ppm, Cr ppm, Fe%, Co ppm, Th ppm, Hf ppm, Ta ppm, Rb ppm.
 
17. Sheet 16: Cypriot_Reference_Group
Purpose and Scientific Context
This sheet contains the INAA reference data for 5,000 specimens representing the two major Cypriot compositional groups: CypH and CypG, as defined by the Bonn laboratory's classification system. CypH encompasses ceramics from the western and southern regions of Cyprus, characterised by elevated Cr from Troodos ophiolite-derived sediments. CypG represents productions from eastern and northern Cyprus with distinct geochemical signatures.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Unique identifier within the Cypriot reference dataset.
Cypriot_Group: Sub-group classification: CypH or CypG.
Site_Origin: Archaeological site on Cyprus: Enkomi, Hala Sultan Tekke, Kalavasos-Ayios Dhimitrios, Maroni-Vournes, Kition, Kouklia-Palaepaphos, Toumba tou Skourou, Maa-Palaeokastro, Pyla-Kokkinokremos, Sinda, Apliki, Athienou, Alassa, Myrtou-Pigadhes, or Episkopi-Bamboula.
Ware_Category: Cypriot ware type: Base Ring I/II, White Slip I/II, White Shaved, Red Lustrous, Monochrome, Plain White, Bucchero, Pithos, or Handmade.
LC_Phase: Late Cypriot chronological phase: LC IIA, LC IIB, LC IIC, LC IIIA, or LC IIIB.
[20 Element Columns]: Concentrations for 20 key elements matching the MYBE reference format for direct inter-group comparison.
 
18. Sheet 17: Local_Ugarit_Group
Purpose and Scientific Context
This sheet presents the INAA data for 5,000 specimens assigned to the local Ugarit production groups (UGA-Local-A, UGA-Local-B, UGA-Local-C, and UGA-Cooking). These groups represent ceramics manufactured from the calcareous clay sources of the Syrian coastal plain near Ras Shamra. The distinctive geochemical signature of these local productions is characterised by very high CaO (15-22%), low Fe (2-3.5%), low Sc (8-14 ppm), and depressed REE abundances relative to Aegean and Cypriot imports.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Unique identifier within the local Ugarit dataset.
Local_Subgroup: Sub-group classification: UGA-Local-A, UGA-Local-B, UGA-Local-C, or UGA-Cooking.
Production_Area: Hypothesised production location within the Ugarit settlement complex.
Clay_Source_Ref: Reference clay source sample identifier linking to Clay_Source_Samples sheet.
Temper_Type / Temper_Pct: Type and volumetric percentage of deliberately added temper inclusions.
[19 Element Columns]: Concentrations for 19 key elements characterising the local production signature.
 
19. Sheet 18: Bivariate_Element_Pairs
Purpose and Scientific Context
This sheet provides pre-calculated element concentrations and ratios for key diagnostic bivariate element pairs used in ceramic provenance scatter plots. Bivariate plots of specific element pairs (e.g., La vs. Sc, Th vs. Hf, Cr vs. Co) have historically been the most intuitive means of visualising compositional group separation. The selection of element pairs follows established archaeometric practice, prioritising combinations of immobile elements that maximise inter-group discrimination while minimising within-group spread.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID / Group: Primary key and compositional group.
La_ppm / Sc_ppm / La_Sc_Ratio: Lanthanum, scandium, and their ratio. La/Sc discriminates between felsic-dominated (high ratio) and mafic-influenced (low ratio) clay sources.
Th_ppm / Hf_ppm / Th_Hf_Ratio: Thorium, hafnium, and ratio. Both HFSE/actinide elements are highly immobile; their ratio reflects heavy mineral assemblage provenance.
Ce_ppm / Eu_ppm / Ce_Eu_Ratio: Cerium, europium, and ratio. Reflects REE fractionation and redox conditions in source sediments.
Cr_ppm / Co_ppm / Cr_Co_Ratio: Chromium, cobalt, and ratio. Cr/Co is diagnostic for ophiolite-influenced vs. continental clay sources.
Fe_pct / Ti_pct / Fe_Ti_Ratio: Iron, titanium, and ratio. Reflects iron oxide and detrital heavy mineral abundances.
Na_pct / Cs_ppm / Na_Cs_Ratio: Sodium, caesium, and ratio. Both alkali elements are susceptible to post-depositional leaching; correlated depletion patterns indicate alteration.
Rb_ppm / K_pct / Rb_K_Ratio: Rubidium, potassium, and ratio. Rb/K fractionation may indicate differential leaching or clay mineral variations.
Sr_ppm / Ca_pct / Sr_Ca_Ratio: Strontium, calcium, and ratio. Sr/Ca reflects carbonate mineralogy and temper contributions.
Sm_ppm / Nd_ppm: Samarium and neodymium concentrations for the Sm-Nd pair, providing additional REE discrimination.
 
20. Sheet 19: Dilution_Corrected
Purpose and Scientific Context
This sheet presents elemental concentrations before and after correction for non-plastic temper dilution using the Bonn modified Mahalanobis dilution factor method. When potters add non-plastic temper materials (quartz sand, calcite, grog, shell) to the clay body, all clay-derived trace element concentrations are systematically reduced proportionally. The dilution factor f (estimated as the scalar that minimises the Mahalanobis distance to the best-matching reference group) enables reconstruction of the original clay composition prior to temper addition.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
Dilution_Factor_f: Best-fit dilution factor estimated from the Bonn method. Values less than 1.0 indicate dilution (temper addition); values greater than 1.0 may indicate concentration (levigation or differential loss of non-plastic material).
f_Uncertainty: Propagated uncertainty on the dilution factor estimate.
CaO_Pct: Calcium oxide content calculated as Ca% x 1.399 (conversion factor from Ca to CaO). Provides a direct estimate of carbonate temper contribution.
Temper_Vol_Pct / Temper_Type: Estimated temper volume percentage and temper material classification from petrographic analysis.
[10 Raw Element Columns]: Uncorrected (raw) concentrations for ten selected elements.
[10 Corrected Element Columns]: Dilution-corrected concentrations computed as raw_concentration / dilution_factor for the same ten elements.
Correction_Method: Statistical method used for dilution correction: Bonn Modified Mahalanobis.
N_Elements_Used: Number of elements included in the dilution factor estimation.
Chi2_Dilution: Chi-squared statistic assessing the goodness-of-fit of the uniform dilution model. Large values indicate non-uniform dilution (e.g., basaltic temper) where the correction may be inappropriate.
Significant_Dilution: Whether the dilution factor deviates significantly from 1.0: Yes or No.
 
21. Sheet 20: Post_Dep_Alteration
Purpose and Scientific Context
This sheet provides a comprehensive assessment of post-depositional chemical alteration for each specimen. Ceramics buried for 3,000+ years in the coastal Syrian environment at Ugarit are subject to systematic chemical changes through groundwater interaction, including alkali leaching (Na, K, Rb, Cs depletion), carbonate precipitation (Ca, Sr enrichment), phosphate enrichment from organic decomposition, and manganese oxide biogenic deposition. These alteration effects represent a major confounding factor for provenance studies, as they can shift individual specimens across compositional group boundaries.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
Burial_Context: Archaeological context of deposition describing the burial matrix.
Soil_pH_Est / Groundwater_Exposure: Estimated soil pH and degree of groundwater interaction at the findspot.
Na/K/Rb/Cs_Depletion_Index: Quantitative indices measuring the depletion of each alkali element relative to its expected concentration. Negative values indicate depletion; positive values indicate enrichment. Calculated as (measured - expected)/expected using immobile element ratios as reference.
Ca/Sr_Enrichment_Index: Enrichment indices for calcium and strontium, reflecting secondary carbonate precipitation from circulating groundwaters.
P_Enrichment_ppm: Phosphorus concentration in ppm, indicative of organic matter decomposition in the burial environment. Values exceeding 5,000 ppm suggest significant phosphate contamination.
Mn/Ba_Enrichment/Alteration_Index: Indices for manganese and barium alteration through biogenic and chemical processes.
U_Mobility_Index: Uranium mobility assessment reflecting redox-driven redistribution in the burial environment.
Secondary_Calcite_Flag: Detection of secondary (post-depositional) calcite in the ceramic fabric: Yes, No, or Trace.
Alkali_Leaching_Severity: Overall severity assessment: None, Mild, Moderate, or Severe.
Overall_Alteration_Grade: Composite alteration grade: A-Pristine, B-Minor, C-Moderate, or D-Severe.
Elements_Affected_Count: Number of elements with concentrations significantly altered by post-depositional processes.
Correctable / Correction_Applied: Whether the alteration is correctable by element exclusion or mathematical correction, and whether such correction was applied.
Na/K_Original_Est: Estimated original (pre-burial) Na and K concentrations reconstructed from immobile element ratios.
Alteration_Mechanism: Dominant chemical alteration mechanism identified.
Burial_Depth_cm / Burial_Duration_Years: Estimated depth and duration of burial.
 
22. Sheet 21: Kiln_Load_Variability
Purpose and Scientific Context
This sheet directly addresses the central research question of the dataset: the magnitude and patterns of trace element heterogeneity within single kiln-load assemblages. Each row represents one specimen within a defined kiln group, with concentrations for provenance-critical elements alongside within-kiln coefficients of variation and the tau incidence statistic (Harbottle 1976). The tau incidence quantifies whether observed compositional spread exceeds analytical uncertainty, distinguishing genuine compositional heterogeneity from measurement noise.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Kiln_Load_ID / Sample_ID: Kiln group identifier and individual specimen identifier.
Position_In_Kiln: Estimated position of the specimen within the kiln during firing: Top-Center, Top-Edge, Middle-Center, Middle-Edge, Bottom-Center, Bottom-Edge, Door-Side, Back-Wall.
Vessel_Type / Firing_Zone: Vessel form and local thermal environment within the kiln structure.
La/Ce/Sm/Eu/Sc/Cr/Fe/Co/Th/Hf/Ca/Na/K: Concentrations for 13 provenance-critical elements enabling direct assessment of intra-kiln variability for both immobile (REE, Sc, Th, Hf) and mobile (Ca, Na, K) elements.
Within_Kiln_CV_La/Sc/Ca/Na: Coefficients of variation (%) for La, Sc, Ca, and Na within the kiln load, computed across all specimens sharing the same Kiln_Load_ID. Low CVs for La and Sc (2-6%) versus high CVs for Ca and Na (8-35%) demonstrate the differential impact of within-kiln processes on different elements.
Kiln_Mean_La / Kiln_SD_La: Mean and standard deviation of La concentration within the kiln load.
Tau_Incidence_Ca: Tau incidence statistic for Ca within the kiln load, quantifying the number of standard deviations by which the observed compositional spread exceeds analytical uncertainty. Values >1.0 indicate genuine compositional heterogeneity beyond measurement error.
 
23. Sheet 22: Clay_Source_Samples
Purpose and Scientific Context
This sheet presents INAA compositional data for 5,000 raw clay source samples collected from geological deposits in the vicinity of Ugarit and across the broader northern Levantine coastal region. These clay samples provide the geochemical baseline against which ceramic compositions are compared, testing the fundamental provenance assumption that ceramic compositions reflect their source clay compositions (modified by temper additions and firing effects).
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Clay_Sample_ID: Unique identifier for each clay source sample.
Source_Location: Named geological sampling locality.
GPS_Latitude / GPS_Longitude: Geographic coordinates of the sampling point in decimal degrees.
Geological_Formation: Geological formation from which the clay was sampled.
Clay_Mineral_Type: Dominant clay mineral assemblage determined by X-ray diffraction.
Sampling_Depth_cm / Color_Munsell: Depth of collection and colour description.
Plasticity_Index: Atterberg plasticity index quantifying the clay's workability.
Calcium_Carbonate_Pct / Organic_Matter_Pct / pH: Geotechnical properties of the raw clay deposit.
[12 Element Columns]: INAA concentrations for 12 key elements enabling comparison with ceramic compositional groups.
Matching_Ceramic_Group: Compositional group whose ceramic compositions best match this clay source.
 
24. Sheet 23: Firing_Temp_Effects
Purpose and Scientific Context
This sheet examines the relationship between estimated firing temperature and elemental concentrations, addressing the question of whether kiln temperature variations within a single firing event can produce compositional heterogeneity that mimics inter-source differences. While INAA-measured trace elements are generally considered temperature-stable, research by Buxeda i Garrigos et al. (2001) demonstrated that very high firing temperatures (>1050 degrees C) can trigger secondary mineralogical reactions that selectively alter Na, K, and Rb through analcime crystallisation and alkali leaching.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
Estimated_Temp_C / Temp_Range: Estimated peak firing temperature and categorical range.
Mineral_Phase / Vitrification_Stage: Diagnostic mineral assemblage and vitrification degree.
Porosity_Pct / Hardness_Mohs: Physical properties related to firing completeness.
Na/K/Rb/Cs: Alkali element concentrations that may be depleted at temperatures >1050 degrees C through analcime crystallisation.
Ca/Fe/Sc/La/Ce/Eu/Th: Concentrations of temperature-stable elements for comparison.
Na_K_Ratio: Na/K ratio as a sensitive indicator of differential alkali loss during high-temperature firing.
Analcime/Gehlenite/Diopside/Mullite/Cristobalite_Detected: Binary flags for detection of specific high-temperature mineral phases by XRD, providing independent confirmation of estimated firing temperatures.
Temp_Classification: Overall assessment of firing adequacy: Well-Fired, Under-Fired, Over-Fired, Optimal, or Variable.
 
25. Sheet 24: QC_Standards
Purpose and Scientific Context
This sheet documents the quality control measurements performed on certified reference materials (CRMs) and in-house pottery standards throughout the analytical campaign. Regular analysis of CRMs at intervals of approximately one per 10-15 unknowns provides ongoing verification of analytical accuracy and precision. The sheet records measured concentrations alongside certified values and computed bias statistics, enabling detection of systematic instrumental drift or calibration errors that could compromise provenance assignments.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Run_ID: Unique identifier for each QC measurement run.
Standard_Name: Name of the certified reference material: SRM-1633b (coal fly ash), SRM-688 (basalt rock), SRM-278 (obsidian), Ohio Red Clay, New Ohio Red Clay, NIST-679, Bonn Pottery Standard, or Old Pottery Standard.
Batch_Date / Analyst: Date of measurement and analyst initials for traceability.
[Element Measured/Certified/Bias Triplets]: For major elements (Na, Al, K, Ca): measured concentration, certified concentration, and percentage bias ((measured-certified)/certified x 100). Bias values within plus or minus 5% indicate acceptable accuracy.
[Element Measured/Certified Pairs]: For trace elements (Fe, Sc, La, Ce, Th): measured and certified concentrations for direct comparison.
Z_Score_Mean: Mean Z-score across all quality-controlled elements, providing a single-number summary of analytical performance for each standard run. Values less than 2.0 indicate satisfactory accuracy.
 
26. Sheet 25: Provenance_Summary
Purpose and Scientific Context
This sheet provides the final integrated provenance determination for each of the 5,000 ceramic specimens, synthesising all preceding analytical evidence: INAA compositional group assignment, Mahalanobis distance classification, PCA cluster membership, dilution correction results, post-depositional alteration assessment, and petrographic/typological concordance. This sheet represents the ultimate deliverable of the analytical campaign, translating chemical data into archaeological interpretations regarding ceramic production origins, trade routes, and exchange networks in the Late Bronze Age Eastern Mediterranean.
Dimensions: 5,001 rows (1 header + 5,000 data records).
Column Descriptions
Sample_ID: Primary key.
Ware_Type / Period / Site: Archaeological context from Sample_Inventory.
INAA_Group: Compositional group from multivariate statistical analysis.
Mahal_Best_Group / Mahal_D2 / Mahal_Prob: Best-matching reference group, squared Mahalanobis distance, and membership probability from the modified Mahalanobis analysis.
PCA_Cluster / Cluster_Agreement: Cluster assignment from PCA-based clustering and agreement with INAA group.
Dilution_Factor / Alteration_Grade: Temper dilution correction factor and post-depositional alteration severity grade.
Final_Provenance / Provenance_Confidence: Integrated provenance determination and confidence level: High, Medium, or Low.
Alternative_Provenance / Alt_Prob: Second-most-likely provenance and its probability, acknowledging classification ambiguity.
Geographic_Origin / Production_Region: Interpreted geographic origin and production region.
Import_Export_Status: Classification as Import, Local Production, Local Imitation, Uncertain, or Re-Export based on concordance of chemical, petrographic, and typological evidence.
Trade_Route: Hypothesised trade route: Aegean Maritime, Cypriot Maritime, Overland Levantine, Coastal Cabotage, Nile-Levant, or Local Production.
Distance_From_Source_km: Estimated straight-line distance from the inferred production source to the findspot at Ugarit, in kilometres.
Chronological_Phase / Cultural_Association: Chronological period and cultural attribution of the ceramic tradition.
Publication_Reference: Published study in which the specimen or its compositional group is described.
Analytical_Notes: Summary notes regarding analytical quality, classification caveats, or interpretive considerations.
 
27. Conclusion and Methodological Notes
The 25-sheet workbook described herein provides a comprehensive, internally consistent dummy dataset that faithfully models the analytical complexity inherent in INAA-based ceramic provenance studies at Late Bronze Age Ugarit. The data generation methodology employed group-specific multivariate normal distributions parameterised from published compositional reference groups, with element-specific coefficients of variation calibrated to replicate the observed within-group spreads reported in the Bonn, MURR, and Berkeley analytical databases.
The dataset is explicitly designed to illustrate the central analytical challenge investigated in this research: that intra-kiln compositional variability, arising from clay source heterogeneity, temper dilution effects, firing-induced alkali mobility, and post-depositional alteration, can generate within-group compositional spreads that overlap with inter-group differences, thereby confounding provenance assignment. The hierarchy of element reliability documented throughout the worksheets confirms that rare earth elements, scandium, thorium, hafnium, and tantalum provide the most robust provenance discrimination, while alkali elements, calcium, and volatile elements require careful evaluation and, in many cases, exclusion from multivariate analysis.
All data values are synthetically generated for research and educational purposes. No values in this workbook represent actual analytical measurements of real archaeological specimens. The compositional patterns, group structures, and statistical relationships are modelled upon published data to ensure scientific plausibility, but should not be cited as empirical evidence in scholarly publications.
