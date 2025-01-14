I list of all variables inthe flowchart plus some that might be emissionsrelated

|Variable | Location | Units given | Definition |
|---------|----------|-----------|--------------|
|**blue**|||
|p_macBaseMAgPIENegCO2|core|No|net negative emissions from co2luc|
|vm_co2captured |**MISSING**||maybe vm_co2capture_cdr defined in 33_cdr|
|vm_co2CCS|core|[GtC/a]|all different ccs|
|vm_emiTeDetail|core|No|energy-related emissions per region and technology|
|**teal**|||
|v_co2capturevalce |**MISSING**|||
|vm_co2CCUshort|39_CCU|[GtC/a]|CO2 captured in CCU te that have a persistence for co2 storage shorter than 5 years|
|vm_emiEnFuel |**MISSING**|||
|vm_emiTeDetailMkt|core|[GtC, Mt CH4, Mt N]|emissions from fuel combustion per region, technology and emission market|
|vm_emiIndCCS|37_industry|[GtC/a]|industry CCS emissions|
|vm_emiTe|core|[GtC, Mt CH4, Mt N]|total energy-related emissions of each region|
|vm_emiTeMkt|core|[GtC, Mt CH4, Mt N]|total energy-emissions of each region and emission market|
|**lightgreen**||||
|vm_emiMac|core|[GtC, Mt CH4, Mt N]|total non-energy-related emission of each region|
|vm_emiMacSector|core|[GtC, Mt CH4, Mt N]|total non-energy-related emission of each region|
|p_macPolCO2luc|/core/input/p_macPolCO2luc.cs4r|No|co2 emissions from landuse change with strong mitigation in MAgPIE|
|**cdr**||||
|vm_emiCdr (DAC +EW)|core|[GtC]|total (negative) emissions from CDR technologies of each region that are calculated in the CDR module. Note that it includes all atmospheric CO2 entering the CCUS chain (i.e. CO2 stored (CDR) AND used (not CDR))|
|v33_emi(te)| **MISSING**|||
|vm_ccs_cdr  |**MISSING**||appears in prepare.R, might be vm_Co2capture_cdr now?|
|**other**||||
|pm_emiExog|core|No|exogenous emissions|
|vm_emiAll|Core|[GtC, Mt CH4, Mt N]|total regional emissions|
|vm_emiAllMkt|core|[GtC, Mt CH4, Mt N]|total regional emissions for each emission market|
|**potentially interesting**||||
|vm_emiCdrAll|core|No|all CDR emissions|
|vm_emiCdrTeDetail|33_cdr|[GtC / a]|gross (negative) emissions from CDR technologies in the CDR module by technology. Includes all atmospheric CO2 that enter the CCUS chain (i.e. CO2 stored (CDR) AND used (not CDR))|
|vm_emiTeDetail|core|No|energy-related emissions per region and technology|
|vm_emiTeDetailMkt|core|[GtC, Mt CH4, Mt N]|emissions from fuel combustion per region, technology and emission market|
|vm_emiCO2Sector|core|||
|vm_emiFgas|core|||
|vm_emiIndBase|37_industry|||
|v_emiEnFuelEx|core|[GtC, Mt CH4, Mt N]|energy emissions from fuel extraction|
