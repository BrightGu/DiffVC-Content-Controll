### MAE-VC: Voice Conversion Based on Learnable Similarity-Guided Masked Autoencoder
<!-- #### [MediumVC: Any-to-any voice conversion using synthetic specific-speaker speeches as intermedium features](https://arxiv.org/abs/2110.02500) -->
#### VCTK
1. F2F, The Norsemen considered the rainbow as a bridge over which the gods passed from earth to their home in the sky.
2. F2M, We also need a small plastic snake and a big toy frog for the kids. 
3. M2F, Since then physicists have found that it is not reflection, but refraction by the raindrops which causes the rainbows. 
4. M2M, Many complicated ideas about the rainbow have been formed.

<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>ADAINVC</td>
      <td>AGAINVC</td>
      <td>MediumVC</td>
      <td>FragmentVC</td>
      <td>MAE-VC</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCTK/F2F/p303_045.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCTK/F2F/p280_315.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCTK/F2F/A_ADAINVC_p303_045TOp280_315.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCTK/F2F/B_AGAINVC_p303_045TOp280_315.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCTK/F2F/C_MediumVC_p303_045TOp280_315.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCTK/F2F/D_FragmentVC_p303_045TOp280_315.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCTK/F2F/E_MAEVC_p303_045TOp280_315.wav"> </audio></td>
     
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCTK/F2M/p239_057.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCTK/F2M/p252_365.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCTK/F2M/A_ADAINVC_p239_057TOp252_365.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCTK/F2M/B_AGAINVC_p239_057TOp252_365.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCTK/F2M/C_MediumVC_p239_057TOp252_365.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCTK/F2M/D_FragmentVC_p239_057TOp252_365.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCTK/F2M/E_MAEVC_p239_057TOp252_365.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCTK/M2F/p232_005.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCTK/M2F/p308_329.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCTK/M2F/A_ADAINVC_p232_005TOp308_329.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCTK/M2F/B_AGAINVC_p232_005TOp308_329.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCTK/M2F/C_MediumVC_p232_005TOp308_329.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCTK/M2F/D_FragmentVC_p232_005TOp308_329.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCTK/M2F/E_MAEVC_p232_005TOp308_329.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCTK/M2M/p246_022.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCTK/M2M/p245_093.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCTK/M2M/A_ADAINVC_p246_022TOp245_093.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCTK/M2M/B_AGAINVC_p246_022TOp245_093.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCTK/M2M/C_MediumVC_p246_022TOp245_093.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCTK/M2M/D_FragmentVC_p246_022TOp245_093.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCTK/M2M/E_MAEVC_p246_022TOp245_093.wav"> </audio></td>
   </tr>
   
</table>

#### VCC2020
1. F2F, A voice on the beach under the cliff began to sing.
2. F2M, The two started to walk back along the road toward town.
3. M2F, This was impregnable, and admitted of neither objection nor restriction.
4. M2M, From a cupboard he pulled out one of his old shirts, which he tore in pieces.

<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>ADAINVC</td>
      <td>AGAINVC</td>
      <td>MediumVC</td>
      <td>FragmentVC</td>
      <td>MAE-VC</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCC/F2F/SEF1_E10054.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCC/F2F/SEF2_E10028.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCC/F2F/A_ADAINVC_SEF1_E10054TOSEF2_E10028.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCC/F2F/B_AGAINVC_SEF1_E10054TOSEF2_E10028.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCC/F2F/C_MediumVC_SEF1_E10054TOSEF2_E10028.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCC/F2F/D_FragmentVC_SEF1_E10054TOSEF2_E10028.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/F2F/E_MAEVC_SEF1_E10054TOSEF2_E10028.wav"> </audio></td>
     
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCC/F2M/SEF1_E10023.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCC/F2M/TEM2_E20019.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCC/F2M/A_ADAINVC_SEF1_E10023TOTEM2_E20019.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCC/F2M/B_AGAINVC_SEF1_E10023TOTEM2_E20019.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCC/F2M/C_MediumVC_SEF1_E10023TOTEM2_E20019.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCC/F2M/D_FragmentVC_SEF1_E10023TOTEM2_E20019.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/F2M/E_MAEVC_SEF1_E10023TOTEM2_E20019.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCC/M2F/SEM1_E10012.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCC/M2F/TEF2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCC/M2F/A_ADAINVC_SEM1_E10012TOTEF2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCC/M2F/B_AGAINVC_SEM1_E10012TOTEF2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCC/M2F/C_MediumVC_SEM1_E10012TOTEF2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCC/M2F/D_FragmentVC_SEM1_E10012TOTEF2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/M2F/E_MAEVC_SEM1_E10012TOTEF2_E10056.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCC/M2M/SEM1_E10001.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCC/M2M/TEM2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCC/M2M/A_ADAINVC_SEM1_E10001TOTEM2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCC/M2M/B_AGAINVC_SEM1_E10001TOTEM2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCC/M2M/C_MediumVC_SEM1_E10001TOTEM2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCC/M2M/D_FragmentVC_SEM1_E10001TOTEM2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/M2M/E_MAEVC_SEM1_E10001TOTEM2_E10056.wav"> </audio></td>
   </tr>
   
</table>

#### LibriSpeech
1. F2F, Moroccan agriculture enjoys special treatment when exporting to Europe.
2. F2M, How does the thing cut the true wall?
3. M2F, Small investors will also be affected, traders said.
4. M2M, Modern electronics has become highly dependent on inorganic chemistry.
<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>ADAINVC</td>
      <td>AGAINVC</td>
      <td>MediumVC</td>
      <td>FragmentVC</td>
      <td>MAE-VC</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/LibriSpeech/F2F/6426_64290_000085_000001.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/LibriSpeech/F2F/8193_116804_000036_000003.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/LibriSpeech/F2F/A_ADAINVC_6426_64290_000085_000001TO8193_116804_000036_000003.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/LibriSpeech/F2F/B_AGAINVC_6426_64290_000085_000001TO8193_116804_000036_000003.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/LibriSpeech/F2F/C_MediumVC_6426_64290_000085_000001TO8193_116804_000036_000003.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/LibriSpeech/F2F/D_FragmentVC_6426_64290_000085_000001TO8193_116804_000036_000003.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/LibriSpeech/F2F/E_MAEVC_6426_64290_000085_000001TO8193_116804_000036_000003.wav"> </audio></td>
     
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/LibriSpeech/F2M/1335_163935_000019_000004.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/LibriSpeech/F2M/8011_280922_000015_000006.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/LibriSpeech/F2M/A_ADAINVC_1335_163935_000019_000004TO8011_280922_000015_000006.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/LibriSpeech/F2M/B_AGAINVC_1335_163935_000019_000004TO8011_280922_000015_000006.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/LibriSpeech/F2M/C_MediumVC_1335_163935_000019_000004TO8011_280922_000015_000006.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/LibriSpeech/F2M/D_FragmentVC_1335_163935_000019_000004TO8011_280922_000015_000006.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/LibriSpeech/F2M/E_MAEVC_1335_163935_000019_000004TO8011_280922_000015_000006.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/LibriSpeech/M2F/1283_129808_000043_000001.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/LibriSpeech/M2F/2254_152831_000004_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/LibriSpeech/M2F/A_ADAINVC_1283_129808_000043_000001TO2254_152831_000004_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/LibriSpeech/M2F/B_AGAINVC_1283_129808_000043_000001TO2254_152831_000004_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/LibriSpeech/M2F/C_MediumVC_1283_129808_000043_000001TO2254_152831_000004_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/LibriSpeech/M2F/D_FragmentVC_1283_129808_000043_000001TO2254_152831_000004_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/LibriSpeech/M2F/E_MAEVC_1283_129808_000043_000001TO2254_152831_000004_000000.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/LibriSpeech/M2M/p246_022.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/LibriSpeech/M2M/p245_093.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/LibriSpeech/M2M/A_ADAINVC_1874_143361_000011_000007TO4243_14929_000012_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/LibriSpeech/M2M/B_AGAINVC_1874_143361_000011_000007TO4243_14929_000012_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/LibriSpeech/M2M/C_MediumVC_1874_143361_000011_000007TO4243_14929_000012_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/LibriSpeech/M2M/D_FragmentVC_1874_143361_000011_000007TO4243_14929_000012_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/LibriSpeech/M2M/E_MAEVC_1874_143361_000011_000007TO4243_14929_000012_000000.wav"> </audio></td>
   </tr>
   
</table>


#### Aishell-3
1. F2F, A voice on the beach under the cliff began to sing.
2. F2M, The two started to walk back along the road toward town.
3. M2F, This was impregnable, and admitted of neither objection nor restriction.
4. M2M, From a cupboard he pulled out one of his old shirts, which he tore in pieces.

<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>ADAINVC</td>
      <td>AGAINVC</td>
      <td>MediumVC</td>
      <td>FragmentVC</td>
      <td>MAE-VC</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/Aishell/F2F/SSB00800116.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/Aishell/F2F/SSB06140066.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/Aishell/F2F/A_ADAINVC_SSB00800116TOSSB06140066.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/Aishell/F2F/B_AGAINVC_SSB00800116TOSSB06140066.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/Aishell/F2F/C_MediumVC_SSB00800116TOSSB06140066.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/Aishell/F2F/D_FragmentVC_SSB00800116TOSSB06140066.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/Aishell/F2F/E_MAEVC_SSB00800116TOSSB06140066.wav"> </audio></td>
     
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/Aishell/F2M/SSB01120062.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/Aishell/F2M/SSB06290090.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/Aishell/F2M/A_ADAINVC_SSB01120062TOSSB06290090.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/Aishell/F2M/B_AGAINVC_SSB01120062TOSSB06290090.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/Aishell/F2M/C_MediumVC_SSB01120062TOSSB06290090.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/Aishell/F2M/D_FragmentVC_SSB01120062TOSSB06290090.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/Aishell/F2M/E_MAEVC_SSB01120062TOSSB06290090.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCC/M2F/SSB00730171.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCC/M2F/SSB18280217.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCC/M2F/A_ADAINVC_SSB00730171TOSSB18280217.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCC/M2F/B_AGAINVC_SSB00730171TOSSB18280217.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCC/M2F/C_MediumVC_SSB00730171TOSSB18280217.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCC/M2F/D_FragmentVC_SSB00730171TOSSB18280217.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/M2F/E_MAEVC_SSB00730171TOSSB18280217.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCC/M2M/SSB02410476.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCC/M2M/SSB18630063.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCC/M2M/A_ADAINVC_SSB02410476TOSSB18630063.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCC/M2M/B_AGAINVC_SSB02410476TOSSB18630063.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCC/M2M/C_MediumVC_SSB02410476TOSSB18630063.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCC/M2M/D_FragmentVC_SSB02410476TOSSB18630063.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/M2M/E_MAEVC_SSB02410476TOSSB18630063.wav"> </audio></td>
   </tr>
   
</table>
