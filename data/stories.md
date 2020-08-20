## Basic Path1
* greet
  - utter_greet
* first_name
  - utter_firstname
* nice_name
  - utter_nicename
* introduce
  - utter_introduce
  - utter_coach
* cool
  - utter_trained
* agree
  - utter_thanks
  - utter_startCH
* understood
  - utter_starting
  - action_restart


  
  
## Basic Path2
* greet
  - utter_greet
* first_name
  - utter_firstname
* nice_name
  - utter_nicename
* introduce
  - utter_introduce
  - utter_coach
* doubting
  - utter_nothuman
  - utter_trained
* agree
  - utter_thanks
  - utter_startCH
* understood
  - utter_starting
  - action_restart

  
  
## Basic Path3
* greet
  - utter_greet
* first_name
  - utter_firstname
* nice_name
  - utter_nicename
* compliment
  - utter_blush
  - utter_introduce
  - utter_coach
* cool
  - utter_trained
* agree
  - utter_thanks
  - utter_startCH
* understood
  - utter_starting
  - action_restart

  
  
## Basic Path4
* greet
  - utter_greet
* first_name
  - utter_firstname
* nice_name
  - utter_nicename
* compliment
  - utter_blush
  - utter_introduce
  - utter_coach
* doubting
  - utter_nothuman
  - utter_trained
* agree
  - utter_thanks
  - utter_startCH
* understood
  - utter_starting
  - action_restart





## LowEsteem Basic Path
* LowEsteem
  - utter_Ack_LowEst
* agree
  - utter_motv_LowEst_Empathy
  - action_restart
  

## LowEsteem Arguments First Path normal
* FirstLowEstEncour
  - utter_motv_LowEst_ifARG_first
* agree
  - utter_motv_LowEst1
  - utter_motv_LowEst2
  - utter_motv_LowEst3
* agree
  - utter_motv_LowEst4
  - utter_motv_LowEst5
* introduce
  -utter_motv_AnotherThing1 
  - action_restart


## LowEsteem Arguments Middle Path normal
* LEstHalfArcourage
  - utter_motv_LowEst_ifARG
* agree
  - utter_motv_LowEst1
  - utter_motv_LowEst2
  - utter_motv_LowEst3
* agree
  - utter_motv_LowEst4
  - utter_motv_LowEst5
* introduce
  -utter_motv_AnotherThing1 
  - action_restart



## LowEsteem Arguments Middle Path convinced
* LEstHalfArcourage
  - utter_motv_LowEst_ifARG
* convinced
  - utter_If_convinced
  - action_restart



## LowEsteem Bob First Path
* BobAwalLE
  - utter_LowEst_IF_Bob_first
* agree
  - utter_motv_LowEst_Bob_empathy
* agree
  - utter_motv_LowEst_Bob1
  - utter_motv_LowEst_Bob2
* agree
  - utter_motv_LowEst_Bob3
  - utter_motv_LowEst_Bob4
  - utter_motv_LowEst_Bob5
* agree
  - utter_motv_AnotherThing2
  - action_restart


## LowEsteem Bob Middle Path normal
* LEStoryMiddle
  - utter_LowEst_IF_Bob
* agree
  - utter_motv_LowEst_Bob_empathy
* agree
  - utter_motv_LowEst_Bob1
  - utter_motv_LowEst_Bob2
* agree
  - utter_motv_LowEst_Bob3
  - utter_motv_LowEst_Bob4
  - utter_motv_LowEst_Bob5
* agree
  - utter_motv_AnotherThing2
  - action_restart
  
  
## LowEsteem Bob Middle Path convinced
* LEStoryMiddle
  - utter_LowEst_IF_Bob
* convinced
  - utter_If_convinced
  - action_restart
  
  
  
## LowEsteem Auth first Path
* AuthFawalLE
  - utter_LowEst_IF_Authority_first
* agree
  - utter_motv_LowEst_auth1
  - utter_motv_LowEst_auth2
* agree
  - utter_motv_LowEst_auth3
  - utter_motv_LowEst_auth4
* agree
  - utter_motv_AnotherThing3
  - action_restart
  
  
## LowEsteem Auth Middle Path normal
* LowEstAuthMid
  - utter_LowEst_IF_Authority
* agree
  - utter_motv_LowEst_auth1
  - utter_motv_LowEst_auth2
* agree
  - utter_motv_LowEst_auth3
  - utter_motv_LowEst_auth4
* agree
  - utter_motv_AnotherThing3
  - action_restart
  
  
## LowEsteem Auth Middle Path convinced
* LowEstAuthMid
  - utter_LowEst_IF_Authority
* convinced
  - utter_If_convinced
  - action_restart











 
## Perfectionism Basic Path
* perfectionism
  - utter_Ack_Perf
* agree
  - utter_motv_Perfectionism_Empathy
  - action_restart
  

## Perfectionism Arguments First Path normal
* ArgPerf1st
  - utter_motv_perfectionism_ifARG_first
* agree
  - utter_motv_perfectionism0
  - utter_motv_perfectionism1
* agree
  - utter_motv_perfectionism2
  - utter_motv_perfectionism3
* understood
  -utter_motv_AnotherThing1 
  - action_restart


## Perfectionism Arguments Middle Path normal
* ArgumentPperfectionism
  - utter_motv_perfectionism_ifARG
* agree
  - utter_motv_perfectionism0
  - utter_motv_perfectionism1
* agree
  - utter_motv_perfectionism2
  - utter_motv_perfectionism3
* understood
  -utter_motv_AnotherThing1 
  - action_restart



## Perfectionism Arguments Middle Path convinced
* ArgumentPperfectionism
  - utter_motv_perfectionism_ifARG
* convinced
  - utter_If_convinced
  - action_restart



## Perfectionism Bob First Path
* StoryPerfFirssst
  - utter_Perf_IF_Bob_first
* agree
  - utter_motv_Perf_Bob_empathy
* agree
  - utter_motv_Perf_Bob1
  - utter_motv_Perf_Bob2
* agree
  - utter_motv_Perf_Bob3
  - utter_motv_Perf_Bob4
  - utter_motv_Perf_Bob5
* agree
  - utter_motv_AnotherThing2
  - action_restart


## Perfectionism Bob Middle Path normal
* PerfMiddleBOB
  - utter_Perf_IF_Bob
* agree
  - utter_motv_Perf_Bob_empathy
* agree
  - utter_motv_Perf_Bob1
  - utter_motv_Perf_Bob2
* agree
  - utter_motv_Perf_Bob3
  - utter_motv_Perf_Bob4
  - utter_motv_Perf_Bob5
* agree
  - utter_motv_AnotherThing2
  - action_restart
  
  
## Perfectionism Bob Middle Path convinced
* PerfMiddleBOB
  - utter_Perf_IF_Bob
* convinced
  - utter_If_convinced
  - action_restart
  
  
  
## Perfectionism Auth first Path
* PerfectioFirrrsstAuth
  - utter_Perf_IF_Authority_first
* agree
  - utter_motv_Perf_auth1
  - utter_motv_Perf_auth2
  - utter_motv_Perf_auth3
* agree
  - utter_motv_AnotherThing3
  - action_restart
  
  
## Perfectionism Auth Middle Path normal
* authorityPerfMiddle
  - utter_Perf_IF_Authority
* agree
  - utter_motv_Perf_auth1
  - utter_motv_Perf_auth2
  - utter_motv_Perf_auth3
* agree
  - utter_motv_AnotherThing3
  - action_restart
  
  
## Perfectionism Auth Middle Path convinced
* authorityPerfMiddle
  - utter_Perf_IF_Authority
* convinced
  - utter_If_convinced
  - action_restart
  


 
## NotConvinced Basic Path
* NotConvinced
  - utter_Ack_NotConvinced
* agree
  - utter_motv_NotConvinced_Empathy
  - action_restart
  
  
  
## NotConvinced Arguments First Path 1
* logicNCfirst
  - utter_motv_NotConvinced_St_im_first
* importance
  - utter_motv_NotConvinced_importance_Empathy
  - utter_motv_NotConvinced_importance1
* agree
  - utter_motv_NotConvinced_importance2
  - utter_motv_NotConvinced_importance3
* agree
  - utter_NC_IF_Studies
* agree
  - utter_motv_NotConvinced_studies_Empathy
  - utter_motv_NotConvinced_studies1
* agree
  - utter_motv_NotConvinced_studies2
  - utter_motv_NotConvinced_studies3
* agree
  -utter_motv_AnotherThing1 
  - action_restart
  
  
## NotConvinced Arguments First Path 2
* logicNCfirst
  - utter_motv_NotConvinced_St_im_first
* studies
  - utter_motv_NotConvinced_studies_Empathy
  - utter_motv_NotConvinced_studies1
* agree
  - utter_motv_NotConvinced_studies2
  - utter_motv_NotConvinced_studies3
* agree
  - utter_NC_IF_importance
* agree
  - utter_motv_NotConvinced_importance_Empathy
  - utter_motv_NotConvinced_importance1
* agree
  - utter_motv_NotConvinced_importance2
  - utter_motv_NotConvinced_importance3
* agree
  - utter_motv_AnotherThing1 
  - action_restart
  
  
  
  
## NotConvinced Arguments First Path second convinced 1
* logicNCfirst
  - utter_motv_NotConvinced_St_im_first
* importance
  - utter_motv_NotConvinced_importance_Empathy
  - utter_motv_NotConvinced_importance1
* agree
  - utter_motv_NotConvinced_importance2
  - utter_motv_NotConvinced_importance3
* agree
  - utter_NC_IF_Studies
* convinced
  - utter_motv_AnotherThing1 
  - action_restart
  
## NotConvinced Arguments First Path second convinced 2
* logicNCfirst
  - utter_motv_NotConvinced_St_im_first
* studies
  - utter_motv_NotConvinced_studies_Empathy
  - utter_motv_NotConvinced_studies1
* agree
  - utter_motv_NotConvinced_studies2
  - utter_motv_NotConvinced_studies3
* agree
  - utter_NC_IF_importance
* convinced
  - utter_motv_AnotherThing1 
  - action_restart
  
  
 

## NotConvinced Arguments Middle Path normal
* logicNC
  - utter_motv_NotConvinced_St_im 
* importance
  - utter_motv_NotConvinced_importance_Empathy
  - utter_motv_NotConvinced_importance1
* agree
  - utter_motv_NotConvinced_importance2
  - utter_motv_NotConvinced_importance3
* agree
  - utter_NC_IF_Studies
* agree
  - utter_motv_NotConvinced_studies_Empathy
  - utter_motv_NotConvinced_studies1
* agree
  - utter_motv_NotConvinced_studies2
  - utter_motv_NotConvinced_studies3
* agree
  - utter_motv_AnotherThing1 
  - action_restart
  
  
## NotConvinced Arguments Middle Path reversed
* logicNC
  - utter_motv_NotConvinced_St_im 
* studies
  - utter_motv_NotConvinced_studies_Empathy
  - utter_motv_NotConvinced_studies1
* agree
  - utter_motv_NotConvinced_studies2
  - utter_motv_NotConvinced_studies3
* agree
  - utter_NC_IF_importance
* agree
  - utter_motv_NotConvinced_importance_Empathy
  - utter_motv_NotConvinced_importance1
* agree
  - utter_motv_NotConvinced_importance2
  - utter_motv_NotConvinced_importance3
* agree
  - utter_motv_AnotherThing1 
  - action_restart
  
  
  
## NotConvinced Arguments Middle Path normal convinced
* logicNC
  - utter_motv_NotConvinced_St_im 
* importance
  - utter_motv_NotConvinced_importance_Empathy
  - utter_motv_NotConvinced_importance1
* agree
  - utter_motv_NotConvinced_importance2
  - utter_motv_NotConvinced_importance3
* agree
  - utter_NC_IF_Studies
* convinced
  - utter_motv_AnotherThing1 
  - action_restart
  
  
## NotConvinced Arguments Middle Path reversed convinced
* logicNC
  - utter_motv_NotConvinced_St_im 
* studies
  - utter_motv_NotConvinced_studies_Empathy
  - utter_motv_NotConvinced_studies1
* agree
  - utter_motv_NotConvinced_studies2
  - utter_motv_NotConvinced_studies3
* agree
  - utter_NC_IF_importance
* convinced
  - utter_motv_AnotherThing1 
  - action_restart
  
  
  
## NotConvinced Arguments Middle Path convinced
* logicNC
  - utter_motv_NotConvinced_St_im
* convinced
  - utter_If_convinced
  - action_restart
  
  
  
## NotConvinced Bob First Path
* BobNCfirst
  - utter_NC_IF_Bob_first
* agree
  - utter_motv_NotConvinced_Bob1
  - utter_motv_NotConvinced_Bob12
* agree
  - utter_motv_NotConvinced_Bob2
  - utter_motv_NotConvinced_Bob3
* agree
  - utter_motv_AnotherThing2
  - action_restart


## NotConvinced Bob Middle Path normal
* BobNC
  - utter_NC_IF_Bob
* agree
  - utter_motv_NotConvinced_Bob1
  - utter_motv_NotConvinced_Bob12
* agree
  - utter_motv_NotConvinced_Bob2
  - utter_motv_NotConvinced_Bob3
* agree
  - utter_motv_AnotherThing2
  - action_restart
  
  
## NotConvinced Bob Middle Path convinced
* BobNC
  - utter_NC_IF_Bob
* convinced
  - utter_If_convinced
  - action_restart
  
  
## NotConvinced Auth Middle Path normal
* authNC
  - utter_NC_IF_Authority
* agree
  - utter_motv_NotConvinced_auth1
  - utter_motv_NotConvinced_auth2
*agree
  - utter_motv_NotConvinced_auth3
  - utter_motv_NotConvinced_auth4
* agree
  - utter_motv_AnotherThing3
  - action_restart
  
  
## NotConvinced Auth Middle Path convinced
* authNC
  - utter_NC_IF_Authority
* convinced
  - utter_If_convinced
  - action_restart
  


## NotConvinced Auth first Path
* authNCfirst
  - utter_NC_IF_Authority_first
* agree
  - utter_motv_NotConvinced_auth1
  - utter_motv_NotConvinced_auth2
*agree
  - utter_motv_NotConvinced_auth3
  - utter_motv_NotConvinced_auth4
* agree
  - utter_motv_AnotherThing3
  - action_restart
  
  
## End Path 
* startExercise
  - utter_start
* understood
  - utter_startExercises
  
