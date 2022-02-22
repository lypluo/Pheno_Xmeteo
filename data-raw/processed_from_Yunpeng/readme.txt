Data description:
1) df_GPP_Meteo_andVIs.rda： the merged GPP,meteorological factors (tidied from Jiangong), and VIs(sourced from Walther et al., 2021) for the sites that with more than 10 years EC data (for different PFTs:DBF,MF,ENF,GRA).
2) df_VIs_Phenos_updated.rda:Phenophases extracted from selected sites(more than 10 years EC data,PFTs only from DBF,MF, and GRA)
3) preprocessed_phenos_andXEP.RDA:pre-processed phenos(sos25,eos90,eos50,eos25,pop...) and XEP(GPP_NT,GPP_DT,and NEP) data
   ==>calculated the GPPmean and GPPcum (and their annual anomaly) during different period:GSL_25sol[sos25,summer solistice],GSL_2590[sos25,eos90],GSL_2550[sos25,eos50],GSL[sos25,eos25].
   ==>only keep the site-years that conforms some critions: 
      #sos25 and eos25 are both available
      #sos should between March and summer solstice
      #eos should later than summer solstice


##pay attention: the datasets might be updated by loose the crition:e.g. select sites that more than 5 years in the future.