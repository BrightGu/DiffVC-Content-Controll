### Compared_with_Baselines （Corresponding to Section 5.3）
1. **DiffVCHW** represents the method derived from this paper "DIFFUSION-BASED VOICE CONVERSION WITH FAST MAXIMUM LIKELIHOOD SAMPLING SCHEME"
2. **The figure** corresponding to the audio refers to the estimation of the Fundamental Frequency (**F0**), which is calculated by function "librosa.pyin".
3. For example, "DiffVCwoCGNG_p240_088TOp245_027.wav" is converted by DiffVC without CGNG based on source speech "p240_088.wav" and target speech "p245_027.wav".

#### F2F
<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>AdaINVC</td>
      <td>AgaINVC</td>
      <td>FragmentVC</td>
      <td>MAE-VC</td>
      <td>DiffVCHW</td>
      <td>DiffVCwoCGNG</td>
      <td>DiffVC</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Compared_with_Baselines/F2F/1/source_p225_004.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Compared_with_Baselines/F2F/1/target_p240_002.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Compared_with_Baselines/F2F/1/AdaINVC_p225_004TOp240_002.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Compared_with_Baselines/F2F/1/AgaINVC_p225_004TOp240_002.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Compared_with_Baselines/F2F/1/FragmentVC_p225_004TOp240_002.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Compared_with_Baselines/F2F/1/MAEVC_p225_004TOp240_002.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Compared_with_Baselines/F2F/1/DiffVCHW_p225_004TOp240_002.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Compared_with_Baselines/F2F/1/DiffVCwoCGNG_p225_004TOp240_002.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Compared_with_Baselines/F2F/1/DiffVC_p225_004TOp240_002.wav"> </audio></td>
   </tr>
  
   
  <tr>
      <td> <img src="Sample-DFHW/Compared_with_Baselines/F2F/1/source_p225_004_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/1/target_p240_002_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/1/AdaINVC_p225_004TOp240_002_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/1/AgaINVC_p225_004TOp240_002_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/1/FragmentVC_p225_004TOp240_002_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/1/MAEVC_p225_004TOp240_002_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/1/DiffVCHW_p225_004TOp240_002_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/1/DiffVCwoCGNG_p225_004TOp240_002_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/1/DiffVC_p225_004TOp240_002_f0.png"> </td>
  </tr>

   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Compared_with_Baselines/F2F/2/source_p264_045.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Compared_with_Baselines/F2F/2/target_p225_039.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Compared_with_Baselines/F2F/2/AdaINVC_p264_045TOp225_039.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Compared_with_Baselines/F2F/2/AgaINVC_p264_045TOp225_039.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Compared_with_Baselines/F2F/2/FragmentVC_p264_045TOp225_039.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Compared_with_Baselines/F2F/2/MAEVC_p264_045TOp225_039.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Compared_with_Baselines/F2F/2/DiffVCHW_p264_045TOp225_039.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Compared_with_Baselines/F2F/2/DiffVCwoCGNG_p264_045TOp225_039.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Compared_with_Baselines/F2F/2/DiffVC_p264_045TOp225_039.wav"> </audio></td>
   </tr>
  
   
  <tr>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/2/source_p264_045_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/2/target_p225_039_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/2/AdaINVC_p264_045TOp225_039_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/2/AgaINVC_p264_045TOp225_039_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/2/FragmentVC_p264_045TOp225_039_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/2/MAEVC_p264_045TOp225_039_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/2/DiffVCHW_p264_045TOp225_039_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/2/DiffVCwoCGNG_p264_045TOp225_039_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/2/DiffVC_p264_045TOp225_039_f0.png"> </td>
  </tr>

  <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Compared_with_Baselines/F2F/3/source_p329_009.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Compared_with_Baselines/F2F/3/target_p225_030.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Compared_with_Baselines/F2F/3/AdaINVC_p329_009TOp225_030.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Compared_with_Baselines/F2F/3/AgaINVC_p329_009TOp225_030.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Compared_with_Baselines/F2F/3/FragmentVC_p329_009TOp225_030.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Compared_with_Baselines/F2F/3/MAEVC_p329_009TOp225_030.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Compared_with_Baselines/F2F/3/DiffVCHW_p329_009TOp225_030.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Compared_with_Baselines/F2F/3/DiffVCwoCGNG_p329_009TOp225_030.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Compared_with_Baselines/F2F/3/DiffVC_p329_009TOp225_030.wav"> </audio></td>
   </tr>
  
   
  <tr>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/3/source_p329_009_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/3/target_p225_030_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/3/AdaINVC_p329_009TOp225_030_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/3/AgaINVC_p329_009TOp225_030_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/3/FragmentVC_p329_009TOp225_030_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/3/MAEVC_p329_009TOp225_030_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/3/DiffVCHW_p329_009TOp225_030_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/3/DiffVCwoCGNG_p329_009TOp225_030_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2F/3/DiffVC_p329_009TOp225_030_f0.png"> </td>
  </tr>
</table>

#### F2M
<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>AdaINVC</td>
      <td>AgaINVC</td>
      <td>FragmentVC</td>
      <td>MAE-VC</td>
      <td>DiffVCHW</td>
      <td>DiffVCwoCGNG</td>
      <td>DiffVC</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Compared_with_Baselines/F2M/1/source_p234_010.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Compared_with_Baselines/F2M/1/target_p326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Compared_with_Baselines/F2M/1/AdaINVC_p234_010TOp326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Compared_with_Baselines/F2M/1/AgaINVC_p234_010TOp326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Compared_with_Baselines/F2M/1/FragmentVC_p234_010TOp326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Compared_with_Baselines/F2M/1/MAEVC_p234_010TOp326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Compared_with_Baselines/F2M/1/DiffVCHW_p234_010TOp326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Compared_with_Baselines/F2M/1/DiffVCwoCGNG_p234_010TOp326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Compared_with_Baselines/F2M/1/DiffVC_p234_010TOp326_160.wav"> </audio></td>
   </tr>
  
   
  <tr>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/1/source_p234_010_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/1/target_p326_160_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/1/AdaINVC_p234_010TOp326_160_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/1/AgaINVC_p234_010TOp326_160_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/1/FragmentVC_p234_010TOp326_160_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/1/MAEVC_p234_010TOp326_160_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/1/DiffVCHW_p234_010TOp326_160_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/1/DiffVCwoCGNG_p234_010TOp326_160_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/1/DiffVC_p234_010TOp326_160_f0.png"></td>
  </tr>

   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Compared_with_Baselines/F2M/2/source_p240_088.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Compared_with_Baselines/F2M/2/target_p245_027.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Compared_with_Baselines/F2M/2/AdaINVC_p240_088TOp245_027.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Compared_with_Baselines/F2M/2/AgaINVC_p240_088TOp245_027.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Compared_with_Baselines/F2M/2/FragmentVC_p240_088TOp245_027.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Compared_with_Baselines/F2M/2/MAEVC_p240_088TOp245_027.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Compared_with_Baselines/F2M/2/DiffVCHW_p240_088TOp245_027.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Compared_with_Baselines/F2M/2/DiffVCwoCGNG_p240_088TOp245_027.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Compared_with_Baselines/F2M/2/DiffVC_p240_088TOp245_027.wav"> </audio></td>
   </tr>
  <tr>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/2/source_p240_088_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/2/target_p245_027_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/2/AdaINVC_p240_088TOp245_027_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/2/AgaINVC_p240_088TOp245_027_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/2/FragmentVC_p240_088TOp245_027_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/2/MAEVC_p240_088TOp245_027_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/2/DiffVCHW_p240_088TOp245_027_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/2/DiffVCwoCGNG_p240_088TOp245_027_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/2/DiffVC_p240_088TOp245_027_f0.png"></td>
  </tr>

  <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Compared_with_Baselines/F2M/3/source_p310_034.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Compared_with_Baselines/F2M/3/target_p326_050.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Compared_with_Baselines/F2M/3/AdaINVC_p310_034TOp326_050.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Compared_with_Baselines/F2M/3/AgaINVC_p310_034TOp326_050.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Compared_with_Baselines/F2M/3/FragmentVC_p310_034TOp326_050.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Compared_with_Baselines/F2M/3/MAEVC_p310_034TOp326_050.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Compared_with_Baselines/F2M/3/DiffVCHW_p310_034TOp326_050.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Compared_with_Baselines/F2M/3/DiffVCwoCGNG_p310_034TOp326_050.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Compared_with_Baselines/F2M/3/DiffVC_p310_034TOp326_050.wav"> </audio></td>
   </tr>
  <tr>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/3/source_p310_034_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/3/target_p326_050_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/3/AdaINVC_p310_034TOp326_050_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/3/AgaINVC_p310_034TOp326_050_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/3/FragmentVC_p310_034TOp326_050_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/3/MAEVC_p310_034TOp326_050_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/3/DiffVCHW_p310_034TOp326_050_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/3/DiffVCwoCGNG_p310_034TOp326_050_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/F2M/3/DiffVC_p310_034TOp326_050_f0.png"></td>
  </tr>
</table>

#### M2F
<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>AdaINVC</td>
      <td>AgaINVC</td>
      <td>FragmentVC</td>
      <td>MAE-VC</td>
      <td>DiffVCHW</td>
      <td>DiffVCwoCGNG</td>
      <td>DiffVC</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Compared_with_Baselines/M2F/1/source_p245_062.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Compared_with_Baselines/M2F/1/target_p307_060.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Compared_with_Baselines/M2F/1/AdaINVC_p245_062TOp307_060.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Compared_with_Baselines/M2F/1/AgaINVC_p245_062TOp307_060.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Compared_with_Baselines/M2F/1/FragmentVC_p245_062TOp307_060.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Compared_with_Baselines/M2F/1/MAEVC_p245_062TOp307_060.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Compared_with_Baselines/M2F/1/DiffVCHW_p245_062TOp307_060.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Compared_with_Baselines/M2F/1/DiffVCwoCGNG_p245_062TOp307_060.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Compared_with_Baselines/M2F/1/DiffVC_p245_062TOp307_060.wav"> </audio></td>
   </tr>
  
   
  <tr>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/1/source_p245_062_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/1/target_p307_060_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/1/AdaINVC_p245_062TOp307_060_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/1/AgaINVC_p245_062TOp307_060_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/1/FragmentVC_p245_062TOp307_060_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/1/MAEVC_p245_062TOp307_060_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/1/DiffVCHW_p245_062TOp307_060_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/1/DiffVCwoCGNG_p245_062TOp307_060_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/1/DiffVC_p245_062TOp307_060_f0.png"></td>
  </tr>

   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Compared_with_Baselines/M2F/2/source_p326_053.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Compared_with_Baselines/M2F/2/target_p240_005.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Compared_with_Baselines/M2F/2/AdaINVC_p326_053TOp240_005.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Compared_with_Baselines/M2F/2/AgaINVC_p326_053TOp240_005.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Compared_with_Baselines/M2F/2/FragmentVC_p326_053TOp240_005.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Compared_with_Baselines/M2F/2/MAEVC_p326_053TOp240_005.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Compared_with_Baselines/M2F/2/DiffVCHW_p326_053TOp240_005.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Compared_with_Baselines/M2F/2/DiffVCwoCGNG_p326_053TOp240_005.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Compared_with_Baselines/M2F/2/DiffVC_p326_053TOp240_005.wav"> </audio></td>
   </tr>
  
   
  <tr>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/2/source_p326_053_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/2/target_p240_005_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/2/AdaINVC_p326_053TOp240_005_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/2/AgaINVC_p326_053TOp240_005_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/2/FragmentVC_p326_053TOp240_005_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/2/MAEVC_p326_053TOp240_005_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/2/DiffVCHW_p326_053TOp240_005_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/2/DiffVCwoCGNG_p326_053TOp240_005_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/2/DiffVC_p326_053TOp240_005_f0.png"></td>
  </tr>

  <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Compared_with_Baselines/M2F/3/source_p347_062.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Compared_with_Baselines/M2F/3/target_p234_013.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Compared_with_Baselines/M2F/3/AdaINVC_p347_062TOp234_013.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Compared_with_Baselines/M2F/3/AgaINVC_p347_062TOp234_013.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Compared_with_Baselines/M2F/3/FragmentVC_p347_062TOp234_013.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Compared_with_Baselines/M2F/3/MAEVC_p347_062TOp234_013.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Compared_with_Baselines/M2F/3/DiffVCHW_p347_062TOp234_013.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Compared_with_Baselines/M2F/3/DiffVCwoCGNG_p347_062TOp234_013.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Compared_with_Baselines/M2F/3/DiffVC_p347_062TOp234_013.wav"> </audio></td>
   </tr>
  <tr>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/3/source_p347_062_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/3/target_p234_013_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/3/AdaINVC_p347_062TOp234_013_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/3/AgaINVC_p347_062TOp234_013_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/3/FragmentVC_p347_062TOp234_013_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/3/MAEVC_p347_062TOp234_013_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/3/DiffVCHW_p347_062TOp234_013_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/3/DiffVCwoCGNG_p347_062TOp234_013_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2F/3/DiffVC_p347_062TOp234_013_f0.png"></td>
  </tr>
</table>

#### M2M
<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>AdaINVC</td>
      <td>AgaINVC</td>
      <td>FragmentVC</td>
      <td>MAE-VC</td>
      <td>DiffVCHW</td>
      <td>DiffVCwoCGNG</td>
      <td>DiffVC</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Compared_with_Baselines/M2M/1/source_p251_002.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Compared_with_Baselines/M2M/1/target_p254_008.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Compared_with_Baselines/M2M/1/AdaINVC_p251_002TOp254_008.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Compared_with_Baselines/M2M/1/AgaINVC_p251_002TOp254_008.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Compared_with_Baselines/M2M/1/FragmentVC_p251_002TOp254_008.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Compared_with_Baselines/M2M/1/MAEVC_p251_002TOp254_008.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Compared_with_Baselines/M2M/1/DiffVCHW_p251_002TOp254_008.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Compared_with_Baselines/M2M/1/DiffVCwoCGNG_p251_002TOp254_008.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Compared_with_Baselines/M2M/1/DiffVC_p251_002TOp254_008.wav"> </audio></td>
   </tr>
 <tr>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/1/source_p251_002_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/1/target_p254_008_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/1/AdaINVC_p251_002TOp254_008_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/1/AgaINVC_p251_002TOp254_008_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/1/FragmentVC_p251_002TOp254_008_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/1/MAEVC_p251_002TOp254_008_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/1/DiffVCHW_p251_002TOp254_008_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/1/DiffVCwoCGNG_p251_002TOp254_008_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/1/DiffVC_p251_002TOp254_008_f0.png"> </audio></td>
  </tr>

   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Compared_with_Baselines/M2M/2/source_p260_040.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Compared_with_Baselines/M2M/2/target_p254_033.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Compared_with_Baselines/M2M/2/AdaINVC_p260_040TOp254_033.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Compared_with_Baselines/M2M/2/AgaINVC_p260_040TOp254_033.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Compared_with_Baselines/M2M/2/FragmentVC_p260_040TOp254_033.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Compared_with_Baselines/M2M/2/MAEVC_p260_040TOp254_033.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Compared_with_Baselines/M2M/2/DiffVCHW_p260_040TOp254_033.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Compared_with_Baselines/M2M/2/DiffVCwoCGNG_p260_040TOp254_033.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Compared_with_Baselines/M2M/2/DiffVC_p260_040TOp254_033.wav"> </audio></td>
   </tr>
 <tr>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/2/source_p260_040_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/2/target_p254_033_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/2/AdaINVC_p260_040TOp254_033_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/2/AgaINVC_p260_040TOp254_033_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/2/FragmentVC_p260_040TOp254_033_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/2/MAEVC_p260_040TOp254_033_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/2/DiffVCHW_p260_040TOp254_033_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/2/DiffVCwoCGNG_p260_040TOp254_033_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/2/DiffVC_p260_040TOp254_033_f0.png"></td>
  </tr>
 <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Compared_with_Baselines/M2M/3/source_p374_002.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Compared_with_Baselines/M2M/3/target_p245_038.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Compared_with_Baselines/M2M/3/AdaINVC_p374_002TOp245_038.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Compared_with_Baselines/M2M/3/AgaINVC_p374_002TOp245_038.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Compared_with_Baselines/M2M/3/FragmentVC_p374_002TOp245_038.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Compared_with_Baselines/M2M/3/MAEVC_p374_002TOp245_038.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Compared_with_Baselines/M2M/3/DiffVCHW_p374_002TOp245_038.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Compared_with_Baselines/M2M/3/DiffVCwoCGNG_p374_002TOp245_038.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Compared_with_Baselines/M2M/3/DiffVC_p374_002TOp245_038.wav"> </audio></td>
   </tr>
  <tr>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/3/source_p374_002_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/3/target_p245_038_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/3/AdaINVC_p374_002TOp245_038_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/3/AgaINVC_p374_002TOp245_038_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/3/FragmentVC_p374_002TOp245_038_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/3/MAEVC_p374_002TOp245_038_f0.png"> </td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/3/DiffVCHW_p374_002TOp245_038_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/3/DiffVCwoCGNG_p374_002TOp245_038_f0.png"></td>
      <td><img src="Sample-DFHW/Compared_with_Baselines/M2M/3/DiffVC_p374_002TOp245_038_f0.png"> </td>
  </tr>
</table>


### Evaluation_on_Mult_Sampling_Timestep （Corresponding to Section 5.4）
1. This section examines the impact of CGNG on model performance across various sampling timesteps.
#### F2F
<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>step20_woCGNG</td>
      <td>step20_CGNG</td>
      <td>step30_woCGNG</td>
      <td>step30_CGNG</td>
      <td>step40_woCGNG</td>
      <td>step40_CGNG</td>
      <td>step50_woCGNG</td>
      <td>step50_CGNG</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/source_f_p240_088.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/target_f_p225_058.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step20_woCGNG_f_p240_088TOf_p225_058.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step20_CGNG_f_p240_088TOf_p225_058.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step30_woCGNG_f_p240_088TOf_p225_058.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step30_CGNG_f_p240_088TOf_p225_058.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step40_woCGNG_f_p240_088TOf_p225_058.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step40_CGNG_f_p240_088TOf_p225_058.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step50_woCGNG_f_p240_088TOf_p225_058.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_H" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step50_CGNG_f_p240_088TOf_p225_058.wav"> </audio></td>
   </tr>
   <tr>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/source_f_p240_088_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/target_f_p225_058_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step20_woCGNG_f_p240_088TOf_p225_058_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step20_CGNG_f_p240_088TOf_p225_058_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step30_woCGNG_f_p240_088TOf_p225_058_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step30_CGNG_f_p240_088TOf_p225_058_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step40_woCGNG_f_p240_088TOf_p225_058_f0.png"></td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step40_CGNG_f_p240_088TOf_p225_058_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step50_woCGNG_f_p240_088TOf_p225_058_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2f/step50_CGNG_f_p240_088TOf_p225_058_f0.png"> </td>
  </tr>
</table>

#### F2M
<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>step20_woCGNG</td>
      <td>step20_CGNG</td>
      <td>step30_woCGNG</td>
      <td>step30_CGNG</td>
      <td>step40_woCGNG</td>
      <td>step40_CGNG</td>
      <td>step50_woCGNG</td>
      <td>step50_CGNG</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/source_f_p240_088.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/target_m_p245_062.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step20_woCGNG_f_p240_088TOm_p245_062.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step20_CGNG_f_p240_088TOm_p245_062.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step30_woCGNG_f_p240_088TOm_p245_062.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step30_CGNG_f_p240_088TOm_p245_062.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step40_woCGNG_f_p240_088TOm_p245_062.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step40_CGNG_f_p240_088TOm_p245_062.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step50_woCGNG_f_p240_088TOm_p245_062.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_H" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step50_CGNG_f_p240_088TOm_p245_062.wav"> </audio></td>
   </tr>
   <tr>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/source_f_p240_088_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/target_m_p245_062_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step20_woCGNG_f_p240_088TOm_p245_062_f0.png"></td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step20_CGNG_f_p240_088TOm_p245_062_f0.png"></td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step30_woCGNG_f_p240_088TOm_p245_062_f0.png"></td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step30_CGNG_f_240_088TOm_p245_062_f0.png"></td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step40_woCGNG_f_p240_088TOm_p245_062_f0.png"></td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step40_CGNG_f_p240_088TOm_p245_062_f0.png"></td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step50_woCGNG_f_p240_088TOm_p245_062_f0.png"></td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/f2m/step50_CGNG_f_p240_088TOm_p245_062_f0.png"> </td>
  </tr>
</table>

#### M2F
<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>step20_woCGNG</td>
      <td>step20_CGNG</td>
      <td>step30_woCGNG</td>
      <td>step30_CGNG</td>
      <td>step40_woCGNG</td>
      <td>step40_CGNG</td>
      <td>step50_woCGNG</td>
      <td>step50_CGNG</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/source_m_p326_051.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/target_f_p234_023.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step20_woCGNG_m_p326_051TOf_p234_023.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step20_CGNG_m_p326_051TOf_p234_023.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step30_woCGNG_m_p326_051TOf_p234_023.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step30_CGNG_m_p326_051TOf_p234_023.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step40_woCGNG_m_p326_051TOf_p234_023.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step40_CGNG_m_p326_051TOf_p234_023.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step50_woCGNG_m_p326_051TOf_p234_023.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_H" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step50_CGNG_m_p326_051TOf_p234_023.wav"> </audio></td>
   </tr>
   <tr>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/source_m_p326_051_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/target_f_p234_023_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step20_woCGNG_m_p326_051TOf_p234_023_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step20_CGNG_m_p326_051TOf_p234_023_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step30_woCGNG_m_p326_051TOf_p234_023_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step30_CGNG_m_p326_051TOf_p234_023_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step40_woCGNG_m_p326_051TOf_p234_023_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step40_CGNG_m_p326_051TOf_p234_023_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step50_woCGNG_m_p326_051TOf_p234_023_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2f/step50_CGNG_m_p326_051TOf_p234_023_f0.png"> </td>
  </tr>
</table>

#### M2M
<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>step20_woCGNG</td>
      <td>step20_CGNG</td>
      <td>step30_woCGNG</td>
      <td>step30_CGNG</td>
      <td>step40_woCGNG</td>
      <td>step40_CGNG</td>
      <td>step50_woCGNG</td>
      <td>step50_CGNG</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/source_m_p347_062.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/target_m_p326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step20_woCGNG_m_p347_062TOm_p326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step20_CGNG_m_p347_062TOm_p326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step30_woCGNG_m_p347_062TOm_p326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step30_CGNG_m_p347_062TOm_p326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step40_woCGNG_m_p347_062TOm_p326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_F" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step40_CGNG_m_p347_062TOm_p326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_G" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step50_woCGNG_m_p347_062TOm_p326_160.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_H" src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step50_CGNG_m_p347_062TOm_p326_160.wav"> </audio></td>
   </tr>
   <tr>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/source_m_p347_062_f0.png" alt="示例图片"></td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/target_m_p326_160_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step20_woCGNG_m_p347_062TOm_p326_160_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step20_CGNG_m_p347_062TOm_p326_160_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step30_woCGNG_m_p347_062TOm_p326_160_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step30_CGNG_m_p347_062TOm_p326_160_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step40_woCGNG_m_p347_062TOm_p326_160_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step40_CGNG_m_p347_062TOm_p326_160_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step50_woCGNG_m_p347_062TOm_p326_160_f0.png"> </td>
      <td><img src="Sample-DFHW/Evaluation_on_Sampling_Timestep/m2m/step50_CGNG_m_p347_062TOm_p326_160_f0.png"> </td>
  </tr>
</table>
