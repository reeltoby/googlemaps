# googlemaps json
https://maps.googleapis.com/maps/api/directions/json?origin=waterloo&destination=welland&key=AIzaSyAUK9DsZZGaTMMpTshAtchs0St92GpjN7M

# valid response
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ3xjvH7NN5YcRGOs8-41AWeg",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJfUmvGstJ04kR5rZtIlVYoLY",
         "types" : [ "locality", "political" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 43.2470448,
               "lng" : -79.22047479999999
            },
            "southwest" : {
               "lat" : 41.3643454,
               "lng" : -92.34257400000001
            }
         },
         "copyrights" : "Map data ©2021 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "814 mi",
                  "value" : 1309275
               },
               "duration" : {
                  "text" : "12 hours 13 mins",
                  "value" : 43957
               },
               "end_address" : "Welland, ON, Canada",
               "end_location" : {
                  "lat" : 42.9921629,
                  "lng" : -79.24825919999999
               },
               "start_address" : "Waterloo, IA, USA",
               "start_location" : {
                  "lat" : 42.4927702,
                  "lng" : -92.34257400000001
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 350
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 42.4906603,
                        "lng" : -92.33940869999999
                     },
                     "html_instructions" : "Head \u003cb\u003esoutheast\u003c/b\u003e on \u003cb\u003eWashington St\u003c/b\u003e toward \u003cb\u003eW 5th St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "yjjbG`trrPr@kAh@cA@?p@cAn@iAh@_Al@gAfAkBbAeB"
                     },
                     "start_location" : {
                        "lat" : 42.4927702,
                        "lng" : -92.34257400000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 mi",
                        "value" : 2204
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 163
                     },
                     "end_location" : {
                        "lat" : 42.4766,
                        "lng" : -92.32226249999999
                     },
                     "html_instructions" : "Take the ramp onto \u003cb\u003eUS-218 S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "s}ibGh`rrPr@mA\\o@DMD]h@cAv@qAlAmBbAcBjCoEtAeCxCiFfAkBfAkBn@iAnCyEfAkB~AqCpA}Bv@qATa@Te@N[Vk@h@{AtAqERk@dAiDRq@L_@N_@LYN]NYP]Ra@`@o@T[d@q@~@{@xAiATQ\\UZQz@_@l@Qj@Qh@Kj@IVCVCXCZAdAAlBCr@?tBE"
                     },
                     "start_location" : {
                        "lat" : 42.4906603,
                        "lng" : -92.33940869999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 mi",
                        "value" : 1851
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 90
                     },
                     "end_location" : {
                        "lat" : 42.4612955,
                        "lng" : -92.3144021
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-380\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eUS-218 S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wegbGbunrP`DExECzBAD?\\CRATEd@ITGRGTIRIZOVOZSt@g@XQd@a@vBwAlEwC~AeAzByAj@a@t@e@lBqAv@g@~B}AxCqBdBiAJGvAaAxAgA^W|@m@r@c@^Q~@c@d@QhAc@b@Ol@Q`@Mr@MvAQbDi@"
                     },
                     "start_location" : {
                        "lat" : 42.4766,
                        "lng" : -92.32226249999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "6.5 mi",
                        "value" : 10502
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 360
                     },
                     "end_location" : {
                        "lat" : 42.4491277,
                        "lng" : -92.19992219999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e71\u003c/b\u003e to merge onto \u003cb\u003eI-380 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eUS-20 E\u003c/b\u003e toward \u003cb\u003eCedar Rapids\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDubuque\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "cfdbG~cmrPTBH@H?JAb@Eh@EVCd@CpAEr@Bx@BjAJxBTrALb@BbAHv@Bj@Cl@EZERENERGTGNGDCDARITMTOVOb@]FGNOLMLQV[NSNW@AN[R_@DIBGBIBIJU@EPk@@EFULe@BOFW@IBM@GF_@?EHk@Dg@@M@Y?C@S@W@k@?A?c@AS?C?QAKA]AE?ICWC]AICU?CGe@Km@G_@YcAwAsD[q@[s@uBkEkAuCw@yBWaAYeAGMOUeAgEEUGWOk@UcAmAcFyAiGo@oCQu@EUKi@Mk@SgAOeAe@_DK_AMgAOcBEi@K{AQqDCu@UoHQkF]cMGmBEgACkAMeEEmAMgEGkBEaBAg@E_BMiDCs@Ae@EsBCiA?sBA]@kB?aA?m@?k@?C@eB@oE?cC?_B@cB?gCBcLDi[?E?wB@uB?i@?gE@cA@aB@]@[D{AB_ADuA@IFqADs@Fy@Bi@H{@LyAJaADg@Fi@Ju@PwA^cCd@mC`@uBf@}BRu@VgAhAyDp@wBTo@Z{@h@uAp@_BXq@`@y@Vi@Tg@l@kAd@w@v@wAb@s@`@s@d@y@|AkCR]~AcDhAeC^_AHSFQDINa@L[HYh@sA`@oANi@Pm@J_@Lc@Ni@XeAT_AR{@Nu@RaAXwAJi@Jm@N{@Jk@Jy@Ju@L_APqAL}APeBLsAHwAHwADaAFeAJsBHgBJwBVuEZsGHoAJiCBe@@a@Dw@HyAFeAFuAHyADo@DaAFmAFcAPuDLkCTeFBa@JoBt@sOF}@HaBF{AFaABi@DcAFmAFqAFyABiADmA@eAByABw@@uA@}A@oDD}N@eCDuM@kF@iFBwFBwHBwHByKBsHAoD"
                     },
                     "start_location" : {
                        "lat" : 42.4612955,
                        "lng" : -92.3144021
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "48.3 mi",
                        "value" : 77759
                     },
                     "duration" : {
                        "text" : "44 mins",
                        "value" : 2644
                     },
                     "end_location" : {
                        "lat" : 41.9357284,
                        "lng" : -91.669158
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork to continue on \u003cb\u003eI-380 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eIA-27 S\u003c/b\u003e, follow signs for \u003cb\u003eInterstate 380 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCedar Rapids\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "azabGnxvqPJk@@C?iB@wA?_A@_@?OBe@Bs@Du@Dg@Dc@DUD[Fa@DYJc@Jg@Jc@Le@Lc@Nc@Pc@N_@JURc@Ra@\\k@Va@\\e@Z]Z]^]VWf@e@FEj@k@tAoAHIv@s@nAkAf@e@l@k@dB}AvCmCv@q@d@]h@_@j@]h@Yp@[x@[^MVGp@Qp@Mb@IbAIlAKbBOF?tCWrBS`AI~AOpBSlDYv@IhCWxCWxBShCWp@GlBOnD]nCWvAMjAKtBSvAOv@G|@GfAKvAK`AKjAK~@Mx@Ml@Ml@Mb@Mz@St@Wd@Q`@ORK~@a@n@[h@Y\\Uh@[b@[j@_@`@Yb@]h@c@b@_@d@a@|@aAr@w@`@g@NSPUT[X_@f@s@d@u@jAkBfC{DnCkExBiDzAeC~@uAlB{CxGkKzBoDvBgDvCqE~C_FhCcEzDgGtDaGPWl@cA^i@FKx@oA^o@b@q@^i@b@u@f@w@j@{@h@{@h@y@h@}@j@{@h@}@h@{@f@w@d@y@f@}@l@eA`@w@d@{@LUd@_Ab@}@Tc@Tc@Re@lB}D^u@pC{FpAiCzBwEjCmFFMRc@`BiD`AqBzIuQdAyBvBkE`@y@vBmEx@cBdCcF`AqBnB_EfA{B~@oBfAwBP_@d@aAr@wA@CdBqDlHgOhE{IbBiDfAyBVk@tFcLnB_ETe@bBkDJS@CnDmHXm@vCaGvGcN`@{@jA_CnByDr@wAvBsEfAyBzCiG`AsBTe@xBmEfBsDr@yA\\u@hBsDrFcLv@}AlAgC~AcD`JyQ?A|E{JrBiEt@}ADKx@kB|@yBzB{FRg@|@{BlA_DjA_DpAeDL]~AeEz@{BtAoDz@{BrAkDb@eAVs@jAuCHS|@uB^{@FMlAoChAiCjAmCfAaCtAaDJUdFcLhAcClBiEfAcC|D}I^y@Xo@j@oAh@oArBwEbAyBbBeEr@qBdAaDpAqEhBuGvAmFhAeE~@oDBKf@iBr@kCl@uBDMp@cC`BiGz@}C@?nAyE|AuFnDsM|A}Fz@yCpAwEpAaF`@wA`BcGjGgUzF}SpCgK@C\\mARs@hAgEpAyENi@ZiA^uA|AuFxAoFZkATy@FUx@wCFU\\mAZmAb@cBvB{HhByGdBiGlC}Jz@cDn@{BrA_Fl@yBZkAv@mChB}GrGaV`@wANi@t@oCZiArA{E?AzJq^|@gDdDuLn@aCpAyEdCaJl@yBh@oB@CXeA|C_Ld@eBFS`DmL`@qATu@Xu@^gAXs@L]JUXu@h@kA\\u@^w@d@_A`@w@`@s@l@aANY\\g@JSj@{@^i@d@o@h@s@rAeBh@q@f@o@nAcBjBcCdCaD^g@dAsA~@oA@CV[nAaBTYDEXa@r@aAX_@RWbAqA~CcEp@{@lA}AlCoDxBsCz@eA\\e@PUjA{Ab@m@~@mAn@{@`@e@\\g@hAwAx@gAf@o@^g@lIwKHKrCuDlA_Bp@{@`C_DBC^g@x@gARUl@y@r@}@|@kAp@{@p@{@|@mA`@i@n@w@b@m@hAyAhAyAf@q@dB}B`@g@n@y@JMxKwNpE}Fn@y@n@{@~@mAn@{@p@{@~@oA~@mAp@{@nA_B`ByB~AuB`BuB^e@`AoAn@y@^g@HKFIj@u@n@{@`@g@`@i@j@w@b@i@^g@|@kA`AqAbC}C^i@pAaBnAcBnA_B^g@~@mAz@gAFKjA{A~@mA`AoA^e@~@oA`AoAn@{@^g@~@mA^e@`AoA~@oA^e@`AoA^e@~@oA~@mAn@y@`AqA`AmA|@oA\\a@`AqA\\e@h@o@x@gA`ByBpBgCvBqClAaBx@eA`C}CZc@jCgDPWtBoC~AuBbBwBzBwCt@eA|@oAb@u@j@_Ah@aAVg@JUHOZo@Zq@\\w@Ti@z@wBp@}ArB_FFO|AwDjAuCl@yA\\y@fAiCVo@\\q@l@uAl@kAb@{@N[fAoB\\k@r@iAl@aAVa@b@m@hAcBb@k@|@mA^g@@C|EwGp@}@Xa@@?`AsA~AyBl@y@nGuIxSiY~DqFZa@b@o@^g@n@{@nBkClAcBp@{@~@qA~@oAj@w@~@qA^g@`AsA~@mA^i@nAcBlAcBlBgCn@}@`AsAlEcG~AuBjCqD`@k@`@i@^g@jCoDpBoCn@}@NSn@{@|@mAnAeB~@mA|AyBp@{@~@oAlBkCn@{@n@{@n@}@lAaBNSFGvByC|AuB`@i@zAuBrAgBjBiCRW^g@\\e@`AqAl@{@^g@NU\\c@`@i@~@oANU~@oANS\\e@l@y@`@m@\\c@PWJOb@o@`@i@V]FI\\e@^e@~@kA^i@`@i@lA_B|BaDnAcBnAcBZc@lCsDdAwAT[f@o@dAwAXa@b@k@~@qA|@mABElA_BDGBEbAwA\\g@l@{@LSPWn@cA`@m@r@kAPYh@_An@gAv@wAbAmBR]Vi@h@cAJS^s@~BwELUv@_Bj@eAf@eAf@aAZm@d@_Aj@gAnBwDdAuBXk@\\s@~A}Cb@}@v@{A~@iBdBiDlCiFhA{BdEkIx@}ArEaJlBwDhEoIlEwI~A_Dv@{A`AmBBEpAgCZm@h@eAf@cAv@{ArAmCDGvC}FdDsGFK^s@Te@Xk@hFeKf@_AVi@hA{Bx@{AXm@Zk@P_@fAoBd@y@h@_Ax@uAx@sAj@}@~@uAd@s@j@w@j@w@p@aA^e@Zc@t@}@t@aA^e@n@s@RWn@s@n@u@t@{@h@k@l@u@p@u@VY|@cA\\a@`@e@l@s@LOn@s@l@q@bAkAb@e@^c@`AgAb@g@Z_@bAkA\\_@`@e@x@}@tA_BhFaG`@e@VYVYvAaBhCwCPSp@w@\\]LQLONQPQnAwA`@g@`@e@r@w@tA}AxAcBnCaDbBkBbAiAjAwArAgBtAsBdAcB`@u@xAoCh@iAPa@Zq@Vk@Zy@t@gBj@yAl@{Ar@eBhAsCfJqUpCeHfGmO~CaIbBgEl@yAbCgGtAkDx@uBz@yBBE~@aC^aA^{@bAgC@CRg@t@mBDKRg@lAyCVm@N[\\u@b@aA^w@x@_BLWP]`@u@h@}@r@mAl@_AbBmC~AiC`F_ItBgDVc@tCqEhAiBtP_XVc@Xa@tSi\\^m@p@cArEkHfGuJpD}FVc@rAsBtBeD~AgCl@aAhAiBf@}@^q@dAiBhAyBj@eATg@v@aBPa@^w@n@{A\\w@HQHU@AlAwC@Eh@qAd@kA|BwFbBaERg@lEoKfEgKnB}E\\{@|BuFd@gAdAiCjAuCfAmCbAaCFOJW`@cAZs@Zu@Xo@f@gARa@Xi@Tg@n@kAXe@Zi@R]R]PYdA{A|@qAl@w@BCb@i@b@i@X[`@c@t@y@x@w@dA_Ab@c@NOlAgA~B{BvAsA~B}BPOrBqBJIx@w@n@m@z@y@fCaCzBuBpCmC@A~A{AlBiB~@}@zA{Al@m@dBgBfIqIdHqHfCmCtAyAbBgBpAsAxA{A^a@h@k@pBuBjBoBtAyAFGb@c@x@{@jAoARSnBsBf@i@TUfAkAjAoAxA}ApJ{J~@cAl@q@BC`@g@^c@^g@Va@\\c@Vc@T_@`@s@t@_Bd@gAVs@JUbCmHTq@lEwMvAgEbA}C`@gAXw@Vq@Ra@Pc@N_@Vg@P]d@{@d@y@Vc@LSV]~@sA|@mAZ]`@c@j@m@^_@RSTS\\Y`@]hA{@ZUVO^WnAs@hAo@VMv@c@bAi@r@_@dAk@LIjBcAh@[f@WjBcAbHyDjEaCt@a@tTyL~A{@vAu@xOoIzFaDvTwL~@g@dBaAdBaAtC}AzBmAzCaBl@]t@_@h@Wb@QVM^M\\KTIXIZIZIVGVG\\G^El@Ib@Ej@CZCh@Aj@AvAAxAAlBCdFCl@Aro@g@r@A|AA`CCp@?dDCP?`FEhEEbEEfGEpAAfCEpDCxAA~AA\\AdAA`BCbBC|BCtDK~l@cB~M_@f@CT?rBIj@AdEKrAEfEMbEMfGQbEK|BIx@GjBOdAOdASrAY`AYtAg@RIh@Sh@SnAm@jAo@~@m@bAw@hAy@h@g@lAiAl@s@DEHI`@e@n@y@PUZe@`@i@NUDGVa@\\k@LWv@wAt@}AfBwDhByDlAiCpAqCr@{ALWt@}Ad@cAr@yAvE}Jj@kATe@vCmG^u@JUlB_EvCmG`EsI^y@jAuBd@y@Ta@\\u@j@q@NQNS\\_@NQ\\WjA{@tAu@jAe@tAa@pCo@b@IhAS|FmAjB_@xCo@~A[r@OlBa@LCb@KpBe@r@SjA]B?tBo@hA_@j@SnAc@fBq@zAm@~@_@x@_@lCmAv@]LIt@_@DAdAk@DCl@_@^SxEmCHEhCyApC_Bj@[dAm@fAo@x@e@r@a@nAo@t@c@VOv@e@TMlAq@~A_AZS@A`@SvAw@z@g@|@g@B?^S`@SZOl@WVK\\Mr@Sj@O`@I\\IRE@?\\EBATCb@Gb@En@E\\C\\Aj@Af@?p@@n@@v@BjDJh@@~@@h@?@?R?VAZ?f@Af@Ct@Cb@EVA\\C\\Ch@Ed@Gh@Eh@Ev@Gd@E|@IhAI^C|@Gl@Cz@CtBI|@Al@Cn@?|A?fB@hA@PAJ?L?H?X@Z@p@BR?D?r@B`ABhADhADx@BvDNN?vCJX@xCH\\@x@BjBFH?~@DpADtABJ?R@P@jBH^Bh@@`@B@?\\@`@@Z@L?T@Z?f@@d@A^?VATA^E`AKRCPC`@IZIn@QJCj@Ql@S`@QZOl@]`@S^W\\W\\WRSFEb@a@j@m@jBkBnBqB`A_AnCoCFIbA_AHKFGPMRONM@Ab@YTOPKj@Wb@QDCPGNEXITGTEj@IPA@AJAH?HAHAH?J?TAP?R?Z?H@H?tBT\\HVF`@Ld@R\\L\\R\\PZRb@\\^ZZXXZ`@b@j@t@BBp@z@rA~Af@j@Z\\RT|@dAhGnHxCfDx@`Av@~@^d@X`@T^PZR^DHLXRf@Nb@Tx@lApElArE`C~IXdA@BRt@Tt@^|@^t@b@n@^d@\\^b@^f@^FDZPB@\\PVJ^L\\Hd@Jl@H`ABb@?PAl@G^Gt@Qh@QXMVMzBsAd@WBC^UlBoA|FwD~@m@`Ao@|E_D^UhBkAj@a@^Up@e@FEfAo@VMxAq@r@SZGD?f@MtBSd@Ed@ChAE`CDZ?J?tA@@?fEBxC@B?tC@b@?fDB~A@~@?nBBlFBdE@fC@N?pHD|@?l@@rDB~A?|@@`BBpE@hHDf@?xAAl@@`@?b@Av@?pBGH?fAIB?|@IjAKVCJClC[~@K|@KhDa@xEk@lBWdBUd@EHAnAQnAOv@IhBS~BWLClBUjAMxAKt@Ez@En@Ej@Af@Ar@?n@@|@@"
                     },
                     "start_location" : {
                        "lat" : 42.4491277,
                        "lng" : -92.19992219999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "16.6 mi",
                        "value" : 26655
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 878
                     },
                     "end_location" : {
                        "lat" : 41.6996318,
                        "lng" : -91.64137129999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue on \u003cb\u003eI-380 S\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "iq}~FfconPnAB|FXbDPrDRx@DtAHT@`CL|@FzAJbCHlBJTBbCL|AHf@Bh@Dt@Br@DF?B@|BLxAHvAHlBLhBJ@?fCLrBJj@DzDRtCN`@BH?zEXtEVfCL~@FdDP`BJpKj@N?xG\\f@Db@BvETL@n@DrAHbADlFZrAHj@BbAB`AB~@BxABtBB~FCvAAvAExAER?lBIvAGfBGrDOlDMvAGj@Cr@ChAE`CK^AtH[hBIPAz@ArFSbCKxAGh@CvCKbDM^AvAExDKt@AnBEvCElBCbAC~@A|ACtCC\\?z@AtLQvCETA@?pMQjKOzCEhBEB?jBG@?^AlAE`AEvBIbAEZCXArDQfFUtAGzFW`@CvEStVgAh@A^C`Ja@pAEvBIvCQdJ_@`DO`DMb@C`AGlBI@?b@Cn@CvCMvAI`CKvBIpESdBI~AGn@CpAGlBK`COb@EhAKjBQ`AK~B[p@Ib@GjAUn@KPE`@Gb@IrA[jBc@hBc@pEgAbDu@nDy@HCJCjAYtBg@hCo@f@MPGb@KzIyBjBe@rBg@lEeAvCu@b@K|@UtA_@XIx@UfBi@nBq@rBu@pCgAxCsAdAe@bF_CbD{Av@]dBy@FC~FqCzBcAZOzCyA|DiBdEqBdD{AxCwAlAk@|@a@fBy@|@a@fAe@DCzBaAfCmAtAq@l@YrDcBRKlCoATKtZoNnDeBpB}@tAq@b@S~Au@hBw@ZOh@QZI\\Md@SlAw@tCuAXM|@[~@Y|@Y`AU~@StAUBAf@I`AK`AIvAI`ACl@A~@Al@?~@BT?h@Dt@D`@D\\@l@?jA?|BBj@@H?b@BxEJbCFrBDzFL~CH`CDdCBvA?vA?nDAxCCbCAnBAvC?dCAjBCdCAbC?~BApXItIE|GCpB?f@AxC?tHE`AAt@?dDG`CK`AIvAO~@KvAUr@MdAUtA[hBg@rAa@f@S|@]|@_@\\Ol@Y`@QFCfD_BvFiCDC`@QXM~Ak@dA_@`Bg@h@Oj@MRG`AQ~@Qj@K~@Ol@G~@Kj@Gj@Ej@C|AGz@A`AClD@|JFdB?D@hA?vIDb@?b@?dIDpB?~BBnJF~A?pA@nLHR?N?rJBz@@jCBlB@zC@jB@lB@bC@rB@pA@xA?tA@vA?lB?vA?b@Ab@?h@?pEE^AhBArCE|AA|AAtAAzAAb@?b@AhAA|GGtKIlFGfPMbEE`CCbC@@?F?b@?lC@~@?b@?H?bB?`C?lB?`@?vA?nB?`C?lB@T?t@@r@@nB?`A?b@?\\?bAA`A?`AAtA@F?b@?h@?lE?z@@rA?@?`@?hA?V?l@?J?V?jC?B?z@?V?xA?tA?vA?vA?^?r@?zA@z@?fA@jA?jA?vC@vA?vA@p@AdACh@APALAf@Ej@Gj@Ij@KVChAWhAW\\Kf@UvBs@"
                     },
                     "start_location" : {
                        "lat" : 41.9357284,
                        "lng" : -91.669158
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 650
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 29
                     },
                     "end_location" : {
                        "lat" : 41.6942203,
                        "lng" : -91.6384113
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue on \u003cb\u003eUS-218 S\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "umo}FpuinPb@W`@Sd@SlAi@TKnAm@n@[jAi@rB_Al@Yz@_@z@_@z@a@rAo@dA_@vAk@tAm@"
                     },
                     "start_location" : {
                        "lat" : 41.6996318,
                        "lng" : -91.64137129999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "50.6 mi",
                        "value" : 81412
                     },
                     "duration" : {
                        "text" : "45 mins",
                        "value" : 2680
                     },
                     "end_location" : {
                        "lat" : 41.60363590000001,
                        "lng" : -90.6852404
                     },
                     "html_instructions" : "Take exit \u003cb\u003e0A\u003c/b\u003e to merge onto \u003cb\u003eI-80 E\u003c/b\u003e toward \u003cb\u003eIowa City\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "{kn}F`cinP^E@?HC\\MRIRG@AHAF?FAH?H@H@H@F@FDFBDBDB@@FHDFDDDHFNFR@DBH@LBF?D@F?F?H?H?J?FAJAJCNEJCHCFCHEHEFGFEDGFGFIDIDIBIBI@E?I?G?GAGAIAGCICGEEEGEEEIKEIEKEMEIAGAECMAMAKAK?MEg@?C?A?AAAMg@?{G@kIA{F?_K?{J?kC?yC?gJ?eB@sB@mA?O@cC?k@@}ADuI@}ABcE@mDBoDDeEDkH?QBsDBgE?o@B_E@o@BaE?g@BwFFaK@aB@q@@{E?Q@u@@u@DqIBoC?o@@{@@sC@i@PuFJoC@UBq@HkAHaABYBUFq@Fu@Hs@Da@Jw@PyA^cCj@gDFa@Hc@TmAl@sD@Al@uDJm@`@aCX_BdAkGfAuGJm@FYBSJk@ZiBRkAJm@F]ZiBf@sCzAaJX_BHe@f@}Cj@aDDWRgAPcAV{ATuATwAd@qCXeBBKBSBMBKRoAJk@Jm@jByKx@{Ej@{D?ANcA`@}CD_@b@}DLkABSBS\\{D^eF@MFeALsBDs@@YHqBHmBH_BD}ABy@@s@@_@@y@DyADkC@sC@eD?kA?qBDcF?oE?iB?M?eA?QBaC?y@?y@?iEB_EAeA@eA?{A?uB@{C@_F@aD?wAC_AAaBI{CGwAM{BO{BWcDo@uIQwBEo@wAaS]yEk@cIEo@WsDIeAKkBE{@A_@AIAe@CWIwEAmAAaB?I@wE?m@@o@@wBFuIBgE@wAD_E?C?k@BwB?CLeQ@w@?y@BcC?K@o@@_C?OBkDJuNBsB?[BaE@}@@qA@{@?o@@c@@iB@uAJqODkF@u@?o@@wA@o@?G@iABkFF_K@SBgF?U?ODmF?AH}M@s@?WBgD@a@B_D@}ADqFB}D@gA@aBBoB?MBiE@yADcE@q@@g@DsBBc@@e@HgBBg@J{AHkAN}AH}@RkBJu@NmANaAHe@L}@N}@\\cBTkAPw@H[XqAVaAzBoIlBiHn@aCr@mC~AeGh@qBNk@t@sCd@gBp@aCp@eC?CfAwD`@}ANk@VaA^uAf@iBNk@@Iz@_DtAiFxBiINk@`@}ALa@Nk@\\qA@Cb@aBl@_CJa@jAmEx@{Cn@cCjAkEZoARu@d@cBd@iBH[DMLe@ZkAd@gBFWDMhAgE?CLa@?ALe@x@{CBM|CoL|@cDxAqF@Ex@}Cf@kBl@_CPo@p@cCLi@r@mCf@kBvAkFnAyEXiAPk@x@}CtAgF?AjAmEPq@Po@@EJe@f@uBd@cCHe@Lm@TyAHm@NeAFa@@KVqBLgA@KDa@BYJoAF}@Fu@D{@Fw@@]Du@@a@DqAB{@BsA@y@?a@@y@DmDHqK?ELkN@iA@aBNoO?o@DiDRyUDmG@GRmWFsFDqFFoFNyRHwGJqLDqEBoDBuBBcC?c@@K@aBB}B?aA@o@@wB@uAAqA?_@?O?iACqAAaAAw@CsAGqBKqCCq@G_BCo@G_BCo@EaAEmACo@Cm@OcEMsDOgDGuBIuBOqDOkEScF?AMsDMgDCq@AeAC}@AqA?EAw@?u@@uB?_@@{@BsAB}@@s@Ba@@[?AD{@Bu@B_@BWD}@Fs@Ba@B_@RqBLqALeAd@mDzBwPHe@RyAR_B|@sGXyBtAaK^qC~@}GBUj@_Et@}FPqAJeALqARaCH}@FaABg@FeABw@Bm@BaADoAD_C@oB?wB?{@CeIAaDGmVAeFC_HCqLAsA?y@?WAuC?YAuB?oBAcB?qBAoD?YAsCAuFAqEAqEAyEAkB?kE?gB@iBBmD@qAF_DDiCD}AZoL@m@@[@SFoCDcB`@yOl@oU@a@HmC@q@Bo@ZmMHoDReH@[B_BBoA@wA@g@B_E?iB?cA?y@AyAEoF?WGgG?AEmFMmNKuJEoFYgZCkC?_@?OE_DIqJCoAAwAGwH?_@EgF?WCuC?{AAgC?k@?qA?}@?o@@iJ@iH@mE?uC?aD@kJ@oI@aE?_B@oC?_B@qNDs_@?e@@iE?qFB}S?q@?_B?c@?qA@{B?U?M?}C?S@qC?W?eA?o@BcW@oC?}D@uB?aA?aE?kA?c@?m@@wC?uC@wE@a@?]DyB@g@?KBo@@c@Bo@@M@_@Dw@Bg@?ABS@YHiAHcA?CFk@Do@JqAF{@Fq@XyDDm@Fo@NoBd@cGRcCt@cKLuAF}@ViDBSL}ADm@Fo@JwATsCDo@VcDh@eHH}@Do@RgCt@_KFm@Do@RmCFm@`@mFDm@JqAn@kIH{@L}ADm@TsC^gFH_ABW?EPwBNoBFaAPoBNwBFw@B[B]PqBNuBBUB_@Fy@H}@Fy@BYF{@F{@Hy@JuABYF{@B]Fy@D]JsAF}@Fw@F{@Hy@Fw@Fw@@ODk@B]Fy@Hy@Fy@F{@Fy@B[Fw@LwAJsAJ{AFw@Da@B[@SDc@LwAJ_ABUJy@Jw@Lu@F]F[F[D[F[Pu@F[Pu@ZoARq@J]Ps@Ty@V{@Le@r@eC`@}ALc@Ni@Lc@Tw@Ru@DMLe@p@cCp@cCxAkFJ_@ZiATu@FWh@mBLe@Ni@`AmDNi@d@aBf@iBdAyDLg@Pi@d@gBPs@T{@r@yCH[Je@\\{A`@kBj@kCl@wCZ{APw@FYVoA`@oBXoAXsAh@iCVmAXsABK\\_Bf@eCNu@Py@Ns@XsAVqAPw@p@cD`@kBn@cDZwALo@Lu@@GLu@RmAD_@Lw@@GFm@D]J{@Jy@Fw@Hy@NoBF{@F{@@]Dy@B]FwA@u@DwA@}@@{@ByA@sB@S@g@?w@@_@@y@?E@oA?a@@u@@a@?{@BqB@wA@q@@g@BmCBcDFyF@yB@YBuCFgG@uA@yADqC@qBB{@?sA@e@?I@o@BqC@wA@q@B}DDwCBoD@_A@y@@{A@y@DmBBsABg@@o@DwA@o@?I@GFsBDmB@a@@{@B{@@a@@O?C?c@@[@_@?YB}ABcB?{@?KBgCBmB@}@@uA@]@wA@wA@W@cB@k@@kA@uB?A@}A?o@?C?]?y@?]?uB?_@A]?y@?{@?{@?q@?E?{@?wA?e@?s@@y@?a@?o@?C@wA@u@BoC?o@RqV@yDNePBaE?GBwABmD@aA?sB@cA?q@BqB@kA@o@?U@wB@uABcC@gB@]?[@[?]?_@@{@@{@BgCDqF@sBBuC@{A?o@@_ABsCBkDBiEByCBoC@uCBsB@sB?u@@}@?K@kB@eC?I@qD@eI?uA@{A?mA?aD@s@?wA?{@?sB@yA?oB?sC@oD?{@@{C?U?]?uB@sB?wA?sB?cA@cA?yA?{A@{@?_@Bu@?a@@]@_@@Y@[@W@_@BY@YB[Bw@Du@LmBDu@?A@IDm@Dq@?APcDDu@BYDs@HyADe@@UHqAFs@Fu@Fw@LoAFu@BWBUHw@Hu@Hs@Hu@B[LkAD_@RiBZeDHu@@?Z_DHy@Hs@Hw@?AFq@NoAHu@BWRkBDk@BMBYNoALoAD[LmAFs@Fk@BOHw@?EHs@Hu@LmA?AVmCJu@B[Hq@?EHs@VgCHu@RsBDY^mDlAkLFg@h@iF@In@eFdA}I~@{HbAkIb@eDLcA^uCDk@\\qCb@sDTkBn@_Ff@wD^gCPmAb@}C@EHi@h@yDBMF_@r@gFzAoKPmAp@qETcBRsA?Ar@aFd@aD@KTyAd@_D\\iCN{@TcBnAyIBUXqBLw@Fe@@KJy@J}@Dc@@QD_@PgBB_@@WJ{ADm@D}@JaCBwAB}@B{@@gA@uLAqC?s@?kC?}A?aB?qE@eM?qU?cBA}A?oCAwCAoE?eFAc@?uCAm@?kC?cAA{E?IAyBA{DA{GAkFAkE?uDAgFC_F?sCAmGA{EA_D?_@AaD?]?o@AoB?oAAoD?aJ?M?uI?mD?o@?M?aC?mB?a@?_PAiJ?gB?qF?_E?O?eC?kA?yF?yA?iH?qC?o@?uC?eHAuD?iC?uC?o@?}A@gFAkB?_B?eI?o@?{@?sA?q@?oB?oA?oA?wB?{A?_C?yD?yCAy@?iAAqAAcACqBAKGuFCaCI}HGkEEsCCgDKkH?KG_FCqBSoPIsGI_IIyF?GEwDAk@?CGmE?a@Ao@A_AE_CA{C?qD@wBDgCJ}DPeJ@c@LkFDaBBiBLeGJoEDgCTcKLuGDiBHeDD{BJmE@YFiCj@uXB}A?ALgFF_C@k@DwBLqGDyE@_B@]?Q?eEAeE?C@a@?yOA{F?aG?o@?]@_DAsC?kI?yI?aE?iF?yC?aH?oB?y@?}K?_I?iI?sC?mDAaF?sB?yA?}@?wF?qF?{J?uC?oF?w@?I?mD?oC?qC?eC?}B?mD?sH?yA?w@AcGAo@@kR?qG?uG?cD?sD?qC?iE?oA?}D?yM?gH?A?}H?cJ?}E?Q?cA@wB@_@?A@[Bi@Bk@@]BUB_@H_ADe@Di@Ju@D_@Ly@D[F[Nu@Pw@BOH_@f@sBPq@`Ia]\\wAzBoJlAcFvDePT_ALk@d@mBh@{BtDyOlAkFv@eD|@wDv@cDj@cC|@wDhAyEJg@@Ch@yBtA_G\\yABMNi@Lg@`F}STaALi@jA{ExDePvB_JZsAVeAZqANs@b@mB^uBTiAb@iCf@iDdAuIBYtAgLp@oFTkBjB_PHm@Ho@fAeJd@uDn@iFJ_Al@eFhBiO`@iDp@wFb@oDZcC~AyMLkAVqB|@sHrA{Kf@kETiBpDoZxA_M|@sH\\mC|AkMZmCD]bAmIJ_AHq@VuBRcBFc@@Id@{Dn@qFx@{GXyBBUp@{Fr@{FTmBJ}@pAqK\\qCXwB\\mCf@qD|@{Gx@cGDYPqAr@oFt@oFzE_^bAsHNmAj@gEF_@Hm@Fc@@If@wDFc@Fm@Jy@Fs@De@B[F{@Fu@Dw@Bg@Bo@B{@DsA@Y@y@@}@@m@?c@?y@AuL?_B?oC?o@?qI?gB?aMAgL?a@?_B?_B?A?kN?uLAeL?kf@?sQ?oO?cGAoA@sAAuA?]?k@?S?E?C?_@?oA"
                     },
                     "start_location" : {
                        "lat" : 41.6942203,
                        "lng" : -91.6384113
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 mi",
                        "value" : 1156
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 42
                     },
                     "end_location" : {
                        "lat" : 41.5970447,
                        "lng" : -90.676689
                     },
                     "html_instructions" : "Take exit \u003cb\u003e290\u003c/b\u003e for \u003cb\u003eInterstate 280\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eUS-6 E\u003c/b\u003e toward \u003cb\u003eRock Island\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMoline\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "wu||Fv}nhPJ_BB{ADcBF}A?C@O@I?G@SDo@Fw@@E@OB[Hi@D[F_@He@FYH_@No@H_@HUH[HUJYL]Vo@JWTg@NYNWLSJQPYJQb@k@NQ`@e@NOLOTSPORONORMPOFCFERMVOPKRKRITKRIRGRGPGVGREl@MPCREZE|@KTCl@Ih@Ej@Ij@GTCj@Gr@I"
                     },
                     "start_location" : {
                        "lat" : 41.60363590000001,
                        "lng" : -90.6852404
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "26.8 mi",
                        "value" : 43087
                     },
                     "duration" : {
                        "text" : "24 mins",
                        "value" : 1419
                     },
                     "end_location" : {
                        "lat" : 41.4402098,
                        "lng" : -90.32875349999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-280 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eUS-6 E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow I-280 E\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Illinois\u003c/div\u003e",
                     "polyline" : {
                        "points" : "ol{|FhhmhPdDc@lAMbAMj@GTCNAXETCTCTC~@Kj@Er@EP?JA`@Az@Cl@?f@?`@?t@?t@?f@?b@?\\?~@?h@?v@?\\?lA?n@?j@?jH?bD?~@@Z?lC?jBD~CJN@j@BT@fAFzAJZBrCXvAL`AJVBh@Fj@Fl@Fj@DrANhBPbBPL@rCXdAJvANXB`@Dr@HdD^@?jCTjSrBf@DjFh@hCTfD^zFh@rCRj@BfAH@?~ADl@?pDCfAAdPg@zIWb@CrGUdGStI[fBEfBGfBEtEKjDE@?b@?bIA~EBX?b@?rDB`FB`A?jBBhJ?nBEjAE\\CbCUVEdG{@lEs@fDg@rWaEbBW`Fy@hFw@~@S\\Eb@IhBYhBYRENCzAUj@Ij@Kn@KRCbAQh@IpASfFu@HAn@IhAIl@EXAbAGZCj@Av@A\\?P?j@?T?z@@vAD~ABpABxFLnCDnCF~GNb@@bA@f@@b@@jBD~DHV@b@@fCFjCF|@An@AVA^Cj@E@?zC_@|EmAl@OpA[vA]vA[`G{AbAW`AWnM{Cz@UdC{@nDgBf@]DAf@_@`@[`@_@\\Yb@e@`@c@Z]X_@^e@^i@v@mA`@o@Zo@Zm@f@cAVs@Xo@Tm@b@eAd@kAb@kAz@wBTi@L[d@kAb@kAn@aB|@yBb@iAdAmCd@kAd@iAhBsE^}@Pa@h@mAd@cAZo@Vi@BEXk@`@y@Tc@v@wAZm@Zm@z@_BrAgCrFmKvBaErGcMlBmDxAqCxBgEpAcCj@eAv@uAp@mAhAiBtCkEd@u@v@mAn@_AXa@x@mAf@u@lAmBl@_Ar@eAhBgCnAeBlAgBlEkGX_@Xa@lIsLXa@X_@lAeBdBeCX_@hBgCV_@jAcBXa@Xa@fBeC~BgDd@s@fDwEr@aA~BgDvDmFnAeBlAeBV]fCoDXa@?Al@y@v@iAr@aA@AhCsDHMl@{@b@o@JO`@k@DEPU@EXa@Za@dBcCjBkCr@aA\\e@RWPWZ]\\_@X]X]b@a@TYl@k@d@a@r@q@LKbA}@POzP}NdB{AhEqDbCeCz@{@r@y@v@{@n@y@|@gA`AoA`DsEt@oAp@oAb@s@d@{@^u@Zo@Xk@Zo@Zq@DIRe@\\y@Vk@v@kBf@sA`@iAj@aBLc@FOTs@hCkI|A_F\\gAh@aBzBgH~F_RdPch@fEwMtAqExB{Gt@aCRq@ZiAZeAT{@`@eBR{@TcAToALo@@EHc@Ls@Hk@Fa@L{@Hg@LcANmAHw@Fs@LyADk@Fq@Bc@Dq@FcAD_AHgBBy@@k@Bs@BwA?{A@wA?c@?kEAcC?sA?m@?oC?oC?sMA{@@UAG?C?[?i@?Q@oBAeC?[?_H?uB?mBAy@AkAAc@A[Ao@Co@E{@E}@Em@I_AIcAKcAUgBKy@EWE]CMMo@O{@G[Mk@?AWgAUaA]iAYaAQg@IUK[GQSk@[y@c@cAa@y@m@oAm@eAUa@MSUa@QWOUGIMQc@s@OSm@{@gHmKk@{@gAaBcBeC]i@_@i@e@u@W]}@qA[e@[g@[i@OUKSYm@We@M[Se@Wm@[w@]aAK[IUUs@M_@k@uBQy@WcAG_@YwAO_AKm@Is@MaAKeAKqAIeAGaAEs@EcACcACw@C{A?eBAiC?qDAqB?o@?K?k@?wMCg]A_L?w@?qBAsCAoAC{AC_ACu@IqBGsAMsBEm@IeAIy@MuAa@aESiBKcAYmCSmB?EMcAW{CSoCOwBMmCI_CAOKsDCsAAw@?w@Ae@?s@?mDAkE?oE?cBAcDA}I?qJA}H?gCAsC?]?O?[?{CAaI?eG?cA@sA@y@@o@FaBBeAD{@@_@B_@@SFaAFu@@YB_@D]NiBD_@D]NqAHw@VkBd@yCH_@Ny@VqAb@qBv@iD^yANi@~CgMf@wBXsAZ}AFa@F[TuAVgBJ}@PyAVqCT{CJ{BDmABy@Bq@@i@@}@@mDCsD?sAC_DAqA?e@AiA?iACqBAiCAeDAcBA_CAy@?}@AsA?{@?}B@iBB}CDqBDyBDuA@y@@]@[Bk@Bk@D}@DsAJsBBa@ZeFF{@Dg@ZiE\\{D~@kLN_CFkADcAD_AD{@BcA@q@@y@@aA@cA?q@?m@?i@AmAA_BGwB?S?IMgFC_AG}Be@iRKmDGqCGwBScIIqCIoCEqBGwBEiBGoBImDCk@?SK{DIoCGqCEoAEcBIqCK{DEcBIqDY{JEwBEsAEyACs@]cNSsFMeDUmEMiCk@yHmA{MOiAg@qEs@oFm@eEKs@o@}Dk@gDg@iCaAwEkAsF[qAYoA[kAg@qBu@qC{@wC{@wCy@iCkAuD}@mCgBsFAEaBeFsAeEu@eCW{@Ss@U_AQw@Ou@Mu@Mo@Mw@M_AOiAMcAEg@CSEm@Gu@Gw@E}@ImBA_@?]AQAs@AiA?w@?{@@y@@s@B{@B}@Bs@Fw@FoAH}@JqAPwAL_AFa@BOJo@F_@Jo@Ha@Nq@Nq@Pu@Rw@Rs@Rs@Ro@Ts@Vo@To@BERi@d@eAn@qA@EP[JSx@yAj@{@FKV]HMb@m@n@{@n@s@t@w@fCkC~ByBJMLMvAuAVYVWzA{AzAyAtCwCLKz@{@pAsA\\[`@a@JIxB{B~@}@jCmCxAwAZ[ZYd@i@p@o@x@y@Z[`@a@bBcBf@e@JKNOxA{ArAqARSh@k@j@i@fBeBr@s@hBgBb@e@j@o@pAwAdAsAb@i@r@aAv@iAl@_Ab@u@DIPYf@{@h@aAr@wAv@aB\\{@lA{Cf@sAPg@^mA^mATw@HW`@yAh@aCTaAz@kEHa@@K`@qCJw@RwAJcABOPoBRgCJuALsCB[DsAB{@BmB@q@B{D@{A?k@FuIH_O?GHyLBqEHcO@{FBkDDmFByD?E?aC@gED}JFuJ@gC?s@@qC"
                     },
                     "start_location" : {
                        "lat" : 41.5970447,
                        "lng" : -90.676689
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "129 mi",
                        "value" : 207609
                     },
                     "duration" : {
                        "text" : "1 hour 55 mins",
                        "value" : 6925
                     },
                     "end_location" : {
                        "lat" : 41.53636789999999,
                        "lng" : -87.96879269999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-80 E\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ix|{FtiifPJeUDyI@sBFqN@iA?eA@_A?G?W@_BBaJ?kECmSAyFAmOAoF?o@G}_@AqG?mBCys@?s]AoQ?iD?mG?m_@?mM?kA?_H?_H?_E?iD@aQAwSAwJAyMC_OAoIG{V?iB?iGA}C?o@C_NAgAAwKCqF?ACoF?QAsDCqGGuMM_VG}LGaLEoLO}YAsCAcF?iD?_AA_LAoX?o@AkMCsf@?qG@}S?qEBm\\@_K@_KBw]?w@@iA?y@?kB?{@@uABgABwABm@BgALaCJoBJwAPqBNsALoAHi@@ORuAPoANu@ToAXwAd@aC@G`@cBd@iBd@aBX_ATq@`@kA^eAd@mAVo@d@eAb@_ABGfA_C`O{ZhBuDtEsJzE{JnFaLpAoCLWhDcHzCmGlAgCzNqZ|A}ChCsFXo@LULYZo@Zq@Xk@Zm@JWf@cAx@aBlAkCXi@t@_Bz@gBz@eBhByDHOP_@`AqBf@eAf@cAXk@FKx@gBt@{Ar@{A^w@n@sAf@eAd@_AN[d@eAd@eAb@gAx@yB@CPg@L_@`@oAf@aBRs@\\qAPs@Pu@No@Jc@Lm@P}@Lo@Lw@RqALu@Ly@Ju@Hy@Js@Hy@J_ATkCB]BWDy@HwAHeBDaAB_A@i@@k@@W@cA?aA@SDyHFgJ@yA@uAFuK@]?e@@qA@sB@uB@{A@qBF}I@uB@uADoE@sB@{@?uA@}@@uA@wA@w@?_@BoC@{@D_I@cBBwD@aA@sBBaDByEDeH@OFkJRa]?OFoI?[DcG?aABcD@y@?_@LiQBgDBeGDiFBgFL_RDkFBgE@uB@uAF{IDkGFuI?M@kA@cDDwE?S?c@@O?i@?U@mAB}B?w@?K@yABgB@mC@_A@{ADcGByC@eCDcG@sBDiEBiE@sB@uA?e@BiB@uA@qB@}@BeE@qCBqB@{A?i@@aBDeF@kCBsDDiFDaHFiJ@gBDeFBmEDqC@k@BgA@c@?Y@[@[By@Bw@DwABc@Bq@B{@JqBF{@FuAPoCTwCJmAFw@RqBFw@TqBJ}@Fm@@EHs@J}@Fa@NkAF]Jw@Jw@DQ?EF[XoBF]Jm@T}Af@cDp@aE?CRmArBwM`@gCHi@V}ALy@Ju@F]ZoB\\wBjAwHLu@He@@EPoA`@aCD[NcA\\yB@AHk@?AHg@Ly@He@PeAZqBJq@t@yEJm@PiARkA~@aGd@yCfCiPh@gDD]F]Jq@VoBVsBNoAD_@d@cEB[RqBH{@NqBJuAF{@Fw@RgDFmALoCJ_CFoBDwBFoC@S@o@BeB@sC@}@?u@?}@?oBAwA?y@EoC?_ACqACoCCyAC}BAkACoB_@w[KqIGgFCuAAkAAeAAiACeAEyAGuAEu@GuAKwASmCGu@OwAWmBS_Be@{CQcA[_BY{AWgAa@_B]sAm@qBy@mCw@uBSi@k@wAu@cBq@yAaAiBa@s@y@wAu@mAwCmEq@_Ao@}@u@cAq@{@_AoAmAeByAyBm@eAs@oAg@_Aa@w@_@w@_@y@Yo@KS[w@{@yBa@gAw@eCi@iBYcA]wAEQQs@WmAYqAc@gCUsAM}@Ko@MgAMcAOsAKmAIs@McBKaBEkAGuAGwACoAC_BA}@?{@?eA?eA@sB@iEHuVB}I@_C?OBiA@iAFqBFuAD}@FkAJ{APqBFu@NyARkBXsBRoARqANu@X}ATeAb@kBZmAPs@Ru@^qA\\eATs@Tq@t@}Bv@{BlAqD`AwC^iATs@`@kANe@Z}@`@kAnAyDPg@tD_Lt@{B~@sCrBiGtAaEd@wAfAeDPg@pCmI|AwEzDkL\\cAb@uA`@wAVaAT{@v@kDh@oCX_Bh@oDh@wD~@mGh@}DjAmIpAiJxAiKzAwKxBuO|@qGpByN|A{KnHsh@@I|CwTnBmNpDkWzIyn@pAoJfD}UbAiHhGkc@n@sEd@eDbAmHLy@DYj@aELw@j@aEd@eD|@uG@CHm@d@kDp@}Ej@_ETeBHi@RaBh@_FLqAH}@ViCH}@JqAPwBHmA?E?ANqBL{BLcCJuBR{DLmCJ{BbA_Tv@gPt@uOHkBl@mMd@sJTeFRcERqDFeBHaBDuADwAFyABcABeAFcCBmBDiB@m@?q@BiC@sB@aA?gB?iB?iB?aBAsAAyEAaGAyDAaCC_J?E?mDE}PCwJGqSEkQ?YAyDCkJAaIAoCA{FAeFEkOAwAAgGCcGAgF?uAAwB?mCASAwD?aCAiBCiBCuCAwBAu@CyBEsBAw@Au@?IEaCE_CEoCEsCEsCEoBEmCEuCEqCAy@AWEyBCsBAw@GoDEsCGmCAyACuAEsBCsBCwACoAOaJEsCGoDIeFEqCC_BAq@EsBEqCEiC?KI_FGoDA]EoCCoCCqC?y@AsB?M?eB@qC@g@?kA@y@BqBBwA@e@@y@@UFqBDsAD{ADsAJsBFqABs@Be@HwAJwAHsAB[Fy@B_@Fu@Di@Dk@BYLuABYD_@B[D]Hw@D_@Fs@Jw@Hw@B[PsAFk@b@sDPuA@KFk@NsAJgABM@UH_AB]B[B[@[B[D{@Bk@Be@Bu@@G@U?S@M@_@@U?C@[?]@{@BsA@wA?_@CgD?[A{@C{@A]GqBAc@KkBA]C[Gy@G}@SaC?EC[C]MsAGq@C[QuBKsAI{@Ea@AWMuAGw@Ea@Gu@KsAGy@OqBEy@Ey@IsAKqBCo@EcAEw@A]IqDA[GcC?OAi@Ai@EuDAaC?}EBoZ@oI@wE?g@?o@@oCD_e@@uE?e@@wC?q@?[?W?e@?mA?uA?mBAy@?o@A_@CwAAs@KiCGmAIqAMiBIaAMsAMuAIq@Ea@QqASwAa@iC]iBWsAWoA[oA[oAa@gB[oA[qAYmA[oAYoAOw@WqAOu@SoAOw@Kw@My@Ku@Kw@Iy@Ks@I{@Gy@Gw@QiCYwFQmDIuBKsBKoBIaBAOGyAKqBKmBGyAIuAEy@GsAMsBIuAUiDOqBSoCk@yGSqBMyAMqAMuAKcAGm@MsAMsAQoBMuASoBMsA?AMuAMuAI{@QiBSsBMwAGy@OuBSgCMsBMsBKsBKsBIsBAYC_AImCEoAAc@EkCEwBCqCAeC?o@AoAW{w@AaDAsAEyKAiFCiEAgGAs@AoFCiFCaHCeH?uACiFC{JEsLEsMAuBCeGCcJ?u@EiJI}U?UCiJAkBCcHAmEEoNA}GAa@?eGAiF?_TA}H?gQAcH?uG?cF?_B?qA?_A?eAAcD?gE?}D?a@?_@?m@?_@?U?U@Q?_@@w@@i@@ODwABy@B{@F_A@UDy@Dw@Fy@Hy@JmADi@P{ALgAJy@Fg@Hk@Lw@Lw@TqAHc@Jm@XsAb@iBLg@\\sA\\iAFSFUNg@Rq@To@\\aAd@oAJWNa@N_@FMDM`@aAr@{At@{Ah@cAdAqBv@{Af@cAl@qA\\{@`@cAb@iANa@^cAJWJ[^kARq@Tu@Pq@\\oAXoAPw@Nm@XsA?AF_@Lk@N_ATwATyANkARcB@KPkBNyAFy@Fw@Dy@Ds@Ba@@YBa@@S@]@]@a@Bs@@]@q@?E@aABgC?]@aB?y@@y@?]@oC?u@@]?uBFkP@wA?y@?s@@}A@uB?oC?wA?]AuAAwACsCASE}BAy@A[EwACy@C_A?ACm@?AAACy@GwAEy@IuAEy@IuAOsBKuAGu@MyAQqBSoBSsBUoBWqBEWQwAYmBQkAIc@Mw@G[Mw@Mu@Mu@Ow@Mu@Ou@Qw@Os@WqAGWI[Ow@ACOo@Mg@CMQu@EQKa@Su@Ok@AGMa@EQSu@Sq@]mACMOe@ACOi@AESq@Sm@Uy@Uq@?ASq@IYKYIWIYIYUs@GUiBaGQm@CGSo@k@qBk@gBQo@Wy@EM_@sAEKMc@AESo@Ss@?A[mAg@iBc@eB?Ae@iBc@mB]{ASaAAAS_A]eB]kBEUQ}@EUO{@UqA?ASqAUsAAGQkASsAMcACMWqBQsAQwASmBIu@K{@MuAC[AKQcBKuAIy@OqBCWCa@Ey@KuAAKIgBMqBE}@OiCYwFCg@?EIuAEw@Ey@o@eMM{BE{@QkDG{@Y{Fo@wLQqDMcCOqCMsBQkDGiAG{AIuACk@E_AGcAOkCi@iKc@mIMiCSuD[yFQeDSeEGoAEaAGeAOaCEq@GgASuDMuCEy@IsAI{AGwAE{AGwACuAGkCAg@A}@AE?Y?O?ECeBAyA?i@?s@A[@sB?cC@iBBmBDoBDkCBo@FgB@s@DmAHqBLaCR}CNgCTwCLyAB[PgBPgBNuAZkC\\kC\\mCV}AXkBN{@BMHm@F_@RkAXcBXiBLw@Hc@NeA@?RsAfA{GJk@?AN}@Ju@TmBB[D]LeAFu@H_ANeBDw@B]Dq@Bm@@e@DgADoABo@?SBgA?o@@}@@c@?K?e@?IAy@?oAAu@Au@Aa@As@Ae@Ci@C_AEq@Cy@CYCi@C]IsAKeAEa@AWMiAGk@Q{AOgAOgAKu@SqA]_Co@aE]}BKq@k@qDUcBUuAQiAMaAS{ASaBGk@Ea@Ge@K}@Gm@CMKiAKcAGy@KeAOiBImAK}AG}@G}@IcBEcAE_AE{@E{@Cq@Ac@E{AIwCCsBC}AA_BAsBA}B?wB?cB?eB?mC@kC?iC?gB?eB?iF?mG?Y@iD?iC?oD?aE?gC?cD?{B?Y?O?_D@oC?yA?oC?aC?oD?]?cC?uA?uA@sC?iC?uB?aA?Q?uB?_K@}N?gH?{K@w@?[@_B?kH?uA@qE?oC@qC?wABwC@oDB{BBqA?o@@iAD{BFuDDgCDuCFwCFqDDyCBsABkB?o@?AD}C@wA@e@@cA@iB@uB@{B@aC@oE?{B?qB?mA?{@?CA_@?wAAyAAkA?e@AaCAmACcECsA?g@CsA?UAo@CmA?QAgAE{AAaAAu@G_DKoFEuBCiBCsACiACmBIgHCuCAuAAuDCcFAgG?_AA_H?iGAgF?yD?eA?kAAqB?oEAqA?o@?yG?eBAcAAwOAoLAqA@uC@qBBoC?[FkDL{DFuBDeAHoBR{DVwDBa@Do@LsAVeDXqCb@wDLgAHo@`@wCZ}BTwARiA|@iFr@qD`@kBRkAn@mCd@kBl@aCn@_ChAyD\\kAt@aCpCeJL_@`@sA@Cz@wCl@wBj@iB|CcKj@oBFQ~@_Dt@aCr@cC|@wC`@qATu@h@gBRs@r@aCh@eB~@}C~@}Ch@gB~ByHhAwDrAmErB{GnBgGJWz@eCLa@xEuMbEiLfFoMf@kAhCmGnAwCdA_CzD}IdB{DtFkMpBqEFKd@gA^{@jAiChAiCr@_B~@wBd@eAd@iAh@iAz@sBd@iAj@yAZw@`@gA`@iA`@gAn@mBh@cBp@yBTs@Ty@Po@Lg@d@aBZiAb@gBHY@E`@aBXwAZqARcAJe@Nu@Nw@TkAN}@He@PaAV{APy@`@{Cl@oE@Md@{D^wD|BqU`CwVnAoMrA}MZ_DRuBfBaRh@cFTiCd@aETwCzAiOl@gGf@eFtAyNx@iIr@cHx@sIhCyWx@oIVeCd@iFXeEPgEJqCBu@HiF@qB?[@eBAgI?kH?c@AmR?_EA}D?cFAsL?iF?}C?gB?q@?s@?oI?oFAqZAoEA_FAuJGcFC}GCoFEwH?k@EeGIkQCqGAaAGiNA{BE{JEkHCcFGkMCwD?gAIeQSy`@C{GMgXMaXMm[Qc`@AwBCcF?_@A{@AqBAuB?q@?IAy@A{@K_DGcAE{@Eg@KiAC]Kw@OoAU_BAGGg@AEGa@G[EUUeAGYG[c@eB?AK_@CIMc@K]Qg@]_AUk@Sm@Wq@[s@i@mASc@MWMUU_@MUIMg@}@GIU_@_CoDo@cA]e@[g@s@mA]m@Yk@[o@c@aA[w@CGSk@O][_A_@kA]iAU_A_@yAYsAEQc@gC[wBWaCOyBEm@MyBI_DAcB?G?g@?aADeDFmE?ID_C@qAFwCDkCFuCBsA@i@@o@@Q?C@g@@g@?O@W@e@@]?I@g@?G@eA?M@Y@e@@mABmBFmEHoF@o@PsKFmDDmD@a@@o@BoBHuDJwCBy@Fw@HcAHcAVwBFc@Hq@Hi@Ji@XiBv@qEh@}Cz@aFbB}JTsARoAd@gCh@}CVyAd@wCp@cEJm@DWRwAPyAP{AJoAL_BDgAH{AD}A@mAB_B?{A?oACsHAeG?kAAkFAuC?uA?{F?AAuI?}E?yA?gB?eA?aB?mC?iB?eC?o@AgA?wO?cHAmK?{J?gI?GAgJAw]?m@?cF?K?AAcGByE@mCBkDFeED_B@mAb@kYFcG@}A@mB?cC?gB?eB?E?i@Aq@AmE?kDAqDCoVAcGAkBA}J?wDEw[Isj@Ms~@CiLGog@?a@?k@Gof@O}fAA_E?o@MkeAAgFAgH?o@AgFCuVA{C?mJEqYEwWC{U?sBAoI?o@AwB?gDCwJ?cC?wCAcJEeX?CCyVAoDCqO?kD?o@AgMAgJAwICeL?o@AcHCiR?oFCiJ?eD?o@C}VAyC?uG?o@A{AAuIAkO?o@Ao@?a@AmP?mDAuC?uCAmD?{BAYCsACwBC_AAQCc@A_@GkACc@?KMeBIgAEw@Gm@MuAK{@CYKu@Ge@Ks@M_AIi@?Am@iD[_BQw@Qs@Oo@Sw@Ok@U}@W{@c@uAW{@_@gAe@qAk@yAc@cA[s@a@{@q@yAe@aAeBuDMUmAkCg@iA_A{Bg@yAo@mB_@kAIY]mASu@[kAQw@YqAYsAO}@i@yCWkBWwBQyAIw@OcBKkAKgBKkCIiBEkBEmB?wAEgC?{BCwFAeB?gCA{CEmKAqDAoEA{BA_C?e@C{GAeBAwBCaC?qCAoDAuDAcECgEAcCAcGAaDGkHI}EM_FUmFIaB]{GCm@UgFCu@Eu@G}BGiBAq@EoBE{DCqDCcCAcDGiLGcKAuBAsBC}DEkGCuD?I?o@?A?s@?yA?E?i@?S@u@BoCDoCB}ADkAHmDHoCRoFBmAJmCBqAP}DRsGPuEf@yOBq@@]b@gMVuHZoKF_ANqEH}BPgFRcHB{@TeOBwBBmE?}B?O@iG?kD?Y@qD?oB?oF?iF?_E?kL?kJ@kJ?_G?}J?{E@mCAcB?uC@}K?yF?gD@iGAq@?oD?iB@oQ@oFAcF@o[?K?oI@qX?{@?yM?cB?mH?cC@uF?q@AwB?{@@oC?sT?eK?_B?u@?m@@aF?gN?}G?o@?wE?eJ?}@BiAAeB@qLAkD@mF?kF?mB?}D?q@?WAuD?yAAgLA}AA_HA_HA}JCqIGsYCcIAsKEkL?sCCmG?oBAcHE{NA}IA}JAqDEiOA{IAgCAyCAaIC_JCaIAqDGyUGwUCaJAuB?mDAuDA}EAmDA_EAiHCoF?o@A_CCcIAqHAoACiMEyLCaG?_EAqCAwDAwDA_IE{GCkCAaFE}IGwJAaAIyMEaKI_Q?YEcJIeKCsDAe@G_GCaBAoCGwMIyLEmICyDEuKCyEIwICcHGmI?]EoNEcOEiOAyBE}IAgDAqDA}EA}B?]?q@CeLAwAG_Q?q@Am@?mA?MCeFKo^C}ICuCAuHCuJEaPMe]AeEMwb@Ogd@?iA?OCmIAoCAo@EmO?w@?GMa_@AmEMq_@?sBEgLCmLAk@I_YGkUAmCAyBEiPCwDEuRAkA?o@CkLAoCAm@?w@C_GEiGA_GCqHC}EAo@C_HEuJEy[A}AEcJCmF?CAkL?UAwBAaEGcT?iCE_KCoICuHCoF?A?m@?ACsLA}AG{CEyAE_AAUOuC_@cFWiCKy@EYCYSwAOw@Ii@YeBg@iCYyAu@_DYaAWaA_@mAa@mA}AiEIWmAsCOYQa@yBwEYm@}@sBoAiCMWyCoGo@sAoGgNq@wAkB_EWk@mHyOg@eACGe@cA_AsBO[_BgDiCuF{AaDuDeI_@{@}KyUSe@Ue@w@aBUg@wE}JUe@uAyCoEoJuJ{SeEwIqFqLcCkFuPm^cKqTgMiXIOKUIQ_AqBkB_EaEyIwBuEGMm@mAmDuHaI}PSe@oEkJ_BiDeHgO{@iBkB{D}C{GeDcHcDgHw@gB]s@a@{@}F_MwCoGyEaKiByDyAcDc@cAaE_JmEqJGKuBoEi@iAaAuBUe@kB_Ek@iAiA}B{@cBs@oA_@o@u@oAQWe@w@a@o@s@eAmDaF_@g@i@u@yFcImCyDkFoHs@aAcCkDQWOQkCwDmFsHiEeGsAkB_DqEyFaIgCoDs@cAgDyEqBsC_@k@Y_@iBiC{AuBaAsA}CmEsAmBc@o@oEkGGIwAqBc@m@iA_BMQKOoEmGiD}EoBmC{AyB}AyB}BaDmAeB}@oAoAgBo@{@o@_A{A}By@qA]i@i@cAk@aAq@oAuAqCg@cAe@eAq@cBc@cAKWKWKYIWKWKYKWKYIYKWIYKYIUUs@IYK[IYIWIYIYSq@Su@GYI[Sy@Qs@IYGWGWGYGWGYG[GYI[GYE[GYGYG[G[E[EOAKG_@Mq@E]GYE[E[E[G[E[E[E[E]E[C[E[E[E[C[Iw@E]CYIy@Gy@C[C]C[C[G{@Gw@Es@A_@C[A]C]A[C]A[A]A]A[A[A]Cy@Aw@EsCi@wq@G_HEoFAoCCmCCuC?S?W?A?AQ_TEoFG{IKwMIoIEeGAoA?KA{AGkHAo@?o@Ao@?o@CyBGuHIcKEsGI_KA}@AqAEoFEoFEaFA}CCcBC}DG}AAo@?O?OEq@Co@GgAQoBKgAG_@QsAE[G[Ko@Ga@GYG]GYOu@G[IYGYIYGYI[IYIWI[IWIYKYIWKYKWIWKWKWKWMYMYWk@MWYm@MWMUYk@MS?AOUACIM[g@c@s@e@m@SYSYQSa@g@]_@QSOQa@a@WW][UUqAqAiBgBc@c@SQQQi@i@i@i@e@e@OMc@c@QOa@a@SQQQQQOOc@c@QQKMOMEEQQMMCCOSQOQQQOQOQOQQAAc@c@MMQQa@a@MMCCQQa@a@c@a@QQQQs@q@cAcAwAuAQOKMKIEEOOUUSSOOSSc@a@u@u@a@a@QQQOQQQQOOc@c@_@_@mCiCc@c@QQQQOOQQIIGGQOCCMMa@a@a@a@a@a@SQGIIGQQAAKKAAMMCCc@a@QQQQQQa@a@QQ[[GEQQOOQQQQQO_@_@wAuASSe@e@m@k@[]m@m@OOc@a@c@a@a@a@a@c@[]GEOQOSGEY_@IIU]CA[e@OUOS]g@]i@]m@KQOY[m@MUYm@Yo@Se@CIYo@ACQg@AEKWUo@Us@IWI[IWI[GQSy@I[G[EQIa@Ka@GYEYY}AOcAKy@E[E[Iu@?AC]Gq@Ea@C_@Eu@CYA]C_@A]AYA]A[A[A]?]Aw@?}@AuA?w@?{@A]?wA?iAAc@?w@?c@AoDAiF?w@?y@AwA?w@A{@?{@A{AAcF?[AcAAoC?oCA_A?i@?]AwA?wA?[AgA?_CAyA?YA[G}DG_CIoCIgCUeHK}DAw@EoB?}@Ac@?iACyC?q@A_@CaDCaDC{CCsEEkHIiLCoEA_@AcC?gAA_@AeCAmCCyBEeHC_DA_CAuACyA?y@EuAIoCIuAA[G{@Gy@Eu@KqAI{@McAQ_BQwAKy@Kq@My@Mu@O{@Kk@S_ACQGYe@sBWcAYkA]iAI]Og@Oa@Sm@i@_BM]GM?AGQ_A_CKSYu@w@cBu@yAs@wAu@kA]m@i@y@GMOUQWaAqAW]W]CECCCCMQA?EGQUIKYa@mA_B_CyCgAwAY_@q@{@o@y@cC_D]c@GGq@}@}AqB}@iA_@g@A?m@w@KOSWAAEEIMm@u@W]k@s@oAaBiNmQY_@u@_AY_@qAaBgGaIk@s@oBgCqAcBa@i@oAgBi@y@MUm@}@KQQW]k@KSOUMSCCCCCEAC[k@QYe@_A[m@KSCEKWi@eAUg@[s@Ym@_@w@EOYo@e@iAc@eAWq@Uo@M[Uo@Us@Uq@CGSo@Sm@Sq@So@CIQi@G[K[c@_Bm@eCk@eCQs@Os@Ou@Ow@Mo@AEOu@Mu@Mw@Ms@Mw@Im@Gk@Ii@?EAGKw@Io@CSAEGg@OsAGo@KcAGk@Eg@Iy@Gw@Gy@KuAMqBCg@Em@?KEm@?GCo@A[Ce@Cs@EsAA]?E?WCy@CwAA{@CcEE}BC_EAo@IqIE}D?o@C_B?o@CoCEqDCoEEoFAIGgHAwCIqFEqCCgBEwGCiBEsDK_NAqBC}B?o@AaAAo@AmA?]EaD?UMcMAiAEeGA{@Ay@?]A]A]Cw@Cy@QwBGk@E_@Mo@Mq@]_BScAScAKs@G]Ky@E[C[G{@CYA[Cy@A{@?[?[?]@[?_@@]@YB]Bc@@UBYD]D]BS?EF[Ly@\\kBZoB\\oBZgBXgBz@{E@EJm@j@gD@IDWD[D]D[BQ@GB_@@E@Q@Y@G@[B]@W?W@e@@[?W?W?SA[A[Ao@AMAMAM?ICYGs@Gu@Gu@Ec@Em@UiDM}AEm@SmC[uEIoAAI?AIsAC[SmCUgDIqAKqAGcAC[M_BWgDa@kFSmCEu@QaCYwDIuAAOAOIgA?QE}@Ca@C}@A[A[Aa@A[?]Ay@Aa@AyBAo@AmCEeFAuA?a@?MC}CCoC?u@AuAAuA?{@A_@?Y@_@?]?]?]@Y?]@Y@u@Bw@@c@@]BcAH_BFgAFgANsCJcBF}ABs@BqAB}@@aA?K@}@@}A?qACqCGiJ?C?o@KaQE_HGeH?}@AuAEuGKgPAsCMeTE{GCaCEuGCiFAi@?EKqRAo@G_KOsXAo@?uAEiEAiCOuUAoCAo@CoFA}AGyIGmLMiTGoLCoFA_BAiCC_AAq@AWE}@E{@AYKuAC[Iy@Gu@Ea@CWA?Ky@U}AIk@G[QcAKi@I]EWGSI_@Qu@Uy@[eAIYOe@[}@?AKYKUM]Si@MYKWg@eAKWMU[m@MU[m@i@{@OQW]IMgA{AGI_AoAOQa@c@a@c@[[SQg@e@eA{@w@i@s@g@qAy@MGMISKICOIKGYMA?ECe@Qe@QQGkBo@YKQEmAYc@I_@I_@I_Do@qBa@i@KQEC?i@My@Os@Qe@Iy@Mg@Ko@OiAYqBw@e@S_@Q}Aw@m@]c@Wo@c@_Aq@y@o@g@a@cA}@WUKKa@a@oAuAg@k@a@g@iA}Ae@o@CEQ[q@eAWe@o@iAu@yAi@mA{@sBKY]aAGO[_A_@mAIYQi@CK[mAOq@IYIa@EQ[}ASgAMu@Im@U}AUaBwAwJE]s@{Eu@oFQiAYqB]cC_CkPUaB"
                     },
                     "start_location" : {
                        "lat" : 41.4402098,
                        "lng" : -90.32875349999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "11.7 mi",
                        "value" : 18809
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 639
                     },
                     "end_location" : {
                        "lat" : 41.5622359,
                        "lng" : -87.75107589999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eI-80 E\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "iqo|F|k|wOyBwO[uBi@wD{ByOEY[}BU{A}CmTIo@M{@[uB_CmPsBwNo@}EqAaJ_B}KIm@QiAgBkMy@wFa@yCOcAScByCySi@qDm@gEIm@iBmMQsASsAcAgHcCcQWeBSkASkAa@uB]}Au@}CQk@Uw@_@oAk@iBYw@Ws@yD{JyAyD[w@g@sAOc@s@kBo@aBmAaD{@}BoAeEi@}Bi@mC_@cCYqBS_CKuAIgAGkAEy@Cy@?SA_@?OAo@A}@IwRCcHAmCKs]Qme@CiEA{D?uAAg@?C?u@G_KEePIiRAiBG_QEgOGyM?o@E{IAiD?y@KqWA_CIoSCkF?iBAu@Ow`@AsMIgJ?{C?_@GmPEeLCoFAuE?ECoCA_BG{M?o@Ao@?AAgC?_B?o@AiA@gDB_BDmCBm@HwBD_AFu@F}@HiANoB@CNyADe@Fi@PmAD]NgAN_A?ALw@Ha@BSF[Li@Jm@DWXsAReA^mBn@gDP{@RaAHi@Lw@F_@Hi@Jy@Hs@Hu@Di@Dc@JkAD}@Be@Bo@D{@BkABoA?g@?o@?E?wBA}BKs]EqHAo@?gACqE?w@AmAGiPE_HCyDKg\\?o@C_KAuAEyM?o@CiGA{DAiD@eC?e@Ag@?c@E_DGoO?o@C_HGkNCgIC_E?cBIcGC{AA[E{@K}ACc@Co@Ce@OcBOiBIy@Iu@IaAAIKk@Io@Kq@Gi@QcAQiAG_@Ic@YuAWmAQy@Qs@IYEQQs@Ka@Uw@g@_B[eAAA]gAyCsIM_@Qg@GQy@aCaBwEiAgDSm@Si@Qi@q@mBaB{E_AmCIUIUGQ]aAg@{AYu@g@}Aq@kBw@}BeDoJUo@Ww@}ByG_@cAu@{Bk@}Am@gBSk@qA{DqAuD?As@uBy@}B"
                     },
                     "start_location" : {
                        "lat" : 41.53636789999999,
                        "lng" : -87.96879269999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 484
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 41.5639862,
                        "lng" : -87.74575849999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eI-80 E\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "_st|Ff{qvO]iAe@_Bc@{A_@}A[uAUgAYuA_@mBe@eC]kBCMa@aB"
                     },
                     "start_location" : {
                        "lat" : 41.5622359,
                        "lng" : -87.75107589999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.5 mi",
                        "value" : 5557
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 191
                     },
                     "end_location" : {
                        "lat" : 41.5828011,
                        "lng" : -87.6860193
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eI-80 E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eToll road\u003c/div\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "}}t|F~ypvOUsAMs@O}@Q}@Q{@AGq@}BK[K]M[Ui@IS_@y@KUGKMUEGMUUa@{@qAEGwAuB}@sAuAaCYi@IOMUy@eB[s@CEa@aAWm@IUc@gAu@sBOc@Us@CG[_AUm@o@mBe@uAkCmHM_@K[[{@mBwFQi@uA_EWq@EIIWQe@Sk@Qi@i@_B_@eASm@Oc@Sg@}BcHa@kACEQg@a@gAqBaGQg@cB{EgAaD_@gACI_@iAw@yBe@sAgAcDSi@yAkEeB}Ea@mAWu@GQMc@CESm@e@sAa@mA_@aAEMkAkDc@kAc@qAaCaHQg@_AoC[_Au@{BUq@Ma@c@uAa@}AOk@EK_BeH?A[cB_@}BAGOeAWiBOkAc@}EImACa@KgBGyAGoA?YCo@?AAo@CsAAu@?g@AeBAwC?sE?o@?aK?kC?K?O?wAAo@?eD?}A?eA?Q?qA?cA?i@As@?s@?iA?}@C_B?}A?IAkB@mA?GDeBHuBPkC"
                     },
                     "start_location" : {
                        "lat" : 41.5639862,
                        "lng" : -87.74575849999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "427 ft",
                        "value" : 130
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 5
                     },
                     "end_location" : {
                        "lat" : 41.58255860000001,
                        "lng" : -87.6844962
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eI-80 E\u003c/b\u003e, follow signs for \u003cb\u003eI-294\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eIndiana\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eToll road\u003c/div\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "osx|FrdevOn@oH"
                     },
                     "start_location" : {
                        "lat" : 41.5828011,
                        "lng" : -87.6860193
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "23.6 mi",
                        "value" : 38023
                     },
                     "duration" : {
                        "text" : "22 mins",
                        "value" : 1328
                     },
                     "end_location" : {
                        "lat" : 41.5846019,
                        "lng" : -87.23498309999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork to stay on \u003cb\u003eI-80 E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eToll road\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Indiana\u003c/div\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "_rx|Fb{dvOJ}@L}@F[Fc@Fa@Hc@N{@Je@Jc@@EF_@DKDQF]Lc@Ha@J_@DMDOJ[FUJ_@Pg@La@Pc@HUL]N]N_@FQFKL[?ARc@@CJWN[Ra@NYN[R]LY@AP[BGLUJSFOLSZm@h@mA`@aARg@Rk@To@Tw@Ne@f@oBJa@H_@P_AJo@N}@BQHm@D[NyAFo@Fw@Bm@F_A@o@@O@O@qA@{A?iA?cD?mFCiD?WA_D?yAAkA?GAGCECCKI?Q?kA@uD?u@?qF?WAkC?_B?_B?u@?]?i@?g@?y@?{@@qFAO?o@?o@?O?uB?{FC_H?eEAwDAaH?wICeHAwG?iAAiA?_EAyEA_I?oJAcH?wBAcCAyC?}AAiA?cAAs@A}@A_@Ca@?UCk@Cg@Ai@C[AWGgAAKAOCWEo@KgAEe@I{@Go@KeAy@eIEe@MoAIw@OeBI}@Es@Eg@Aa@Eu@Cq@C}@Aa@Ao@AO?Q?_@Ac@?y@Aa@?qA?eC?iA?oB?_@@_E?o@?GAyGCsGBkH@oU?u@?qF@iE?mQ@cF?A?aA?aB?u@@eA@m@DoDBm@@]@[Ba@@g@Be@Bg@Dk@@[HeAFu@NwBv@wKTqC@MNqBHeAHgAJqATmCH{APkBDs@Ba@Dc@Dg@B]Be@De@B_@HaAFy@?KDi@Ba@DeAB_@FsADyBBgA?W@i@?}@@g@?wA?y@?cBAkB?_E?I?e@?yA?eE?o@?eB?{H?q@A{A?iA?A?E?o@?W?M?aA@OAI@U?g@AoA?uO?iM?c@?cCAyMAoF?cG?uA?W?cLAwK@sF?mC?{ABg@CkG?sECoG?A?A?E?A?G?i@?C?Q?A?A?u@?sF@qL?aGAwKAgH?i@?A?cC?{@?y@?u@DmD?o@?q@AiI?qHAaD?oC?aH?mCAgC?aAAcA?oF?o@?o@?_K?o@?iD?gH?yB?qA?o@@m@FqD@cABeABi@?CJgBJgBFy@FgAJoAHs@Di@Fi@Hu@RcBL}@Hk@\\yBN{@f@uCz@{EP_AP_AfAkG\\gBRiAr@{Dv@mEN{@Fa@F_@Hm@F_@BYZcCNsANcBNaCLiBDq@Bk@@S@[B_@@OBo@DsADmB@m@@uA?u@?eA?cB?S?sAAqBA_C?s@AqB?MAiE?eACiP?OAyEC}ICyHAcE?oAAiFAwCAyA?cBA{BAaF?e@AsE@_G?KC_E?W@e@AsD?gJ?G?sA?uA?uL@sB@sB?aB@cA?aA?g@@e@?U?i@?y@@yI?o@?oC?_B@}D@mK@uF?_EBqR?uF?uB@sB@_D@oL?m@?A?eC?I@aE?}A?mD@oI@wIB_\\@{EBsBDqBB{@JwBHiBJwAJ}APkBPgBReBJ_ARwAXgBF]N}@Jm@Lm@XqAVqAXgA?CLg@DQf@gB`AsDh@kBd@kBPu@ZoAJe@\\eBJk@Ha@F_@Lu@Ny@Fa@Jq@D[BOFi@ToBTsBHu@L_BFs@NcCDw@@MBg@?E@_@BY?QBy@DwABuABaB?y@@oA?{A?oF?E?iF@wK?oF?_E?w@?gC@aK?oF?}E?aH@_I?cD?qJ@yC@cFBeH@oL?o@@o@?gB@iN?oA?[?_V@qB?gJBqM?[?qA?q@B_TBwUBiM?_BDuR?kIDcY?mDB{P@qB?o@?oF@aK?_K@_B?A?wBDmHBwCDwABs@DuADeA?KBc@@[@SBa@Bu@FaAFmABi@LiBXiEToCRuBB[Da@LuAVmC\\gDTiCVgC@S\\yDPoBHgAHoAPqCFgAHcBJeC@WDeADgADyADkBDsB@kAB_B@iD@uF?iCDqa@?o@BuQ@{O@mGB_K@qI@oJBqR@_I@yH?gF?gB?QA{@AuAAkBEgBCiBC}@C}@Cc@A]Cs@O_E?KKoBCe@KqBGy@IcAIaAO{BGg@]}DYoCK{@SkBq@iG_@oDIm@WcCk@qFkAkKEWCUm@iFmAcL_BaOgAaKWaCMcAK}@[qCuAiMm@sF[qCSiBSiBSoBUqBE]E_@Gi@Gi@?AKy@CWE[KeAYqCGq@Io@Iq@C[OwAQwAi@aF[sCCYUoBUyB]kD[qCCSq@_Gy@mHu@aHc@wDYcCg@uDYuBS{Ak@aEq@qEa@iCIm@Ia@YcBc@mCmAwGa@wB]cBq@cDiDwPcHc]c@}B[sA_@mBa@uB{EiUqAwGaAsE_AmEAEGW?AY_Bi@gCYuAs@oD_BuHk@kCa@cB"
                     },
                     "start_location" : {
                        "lat" : 41.58255860000001,
                        "lng" : -87.6844962
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "63.9 mi",
                        "value" : 102838
                     },
                     "duration" : {
                        "text" : "56 mins",
                        "value" : 3368
                     },
                     "end_location" : {
                        "lat" : 42.1288312,
                        "lng" : -86.37639159999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-94 E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Michigan\u003c/div\u003e",
                     "polyline" : {
                        "points" : "w~x|FramsOk@yBa@}A]mA_@qAa@sAWy@Uw@c@{AOe@AAEOAAu@_CqBqFa@eAsAaDKWy@kBi@gAiFyK{@eB_BcDEIWg@EKwBiEoAmC{A{CeAuBi@gAg@eAUe@AASc@eCaFu@}AOYe@cAgA}Bg@aAg@cAuBgEMWWi@Wi@Wo@[w@[w@Qg@i@aBUu@Qq@Sw@Oq@EOKi@Oq@Ie@ACIi@Kq@My@CYQyAa@uDg@qESuBi@aF}AwNSmBSsBKkAqAuLU}BK}@i@aF_A_JUqBGi@I{@Q}Am@yFe@wEm@yFGk@Kw@KoAYcCa@wDU{BQwAc@oEQaBQiBKu@Gk@KoAM}AAOAKAK?IAOAMC]Co@K_BIoCGmDAuFJgYDsH@aFD_K@uABsIDoOBsDB}D?{@?O@iA?eA?A@gA@_EDkG@sE@o@@_E?o@B_E@_BBoI@o@@oC?o@@w@@aF@oC?q@@_CAwCAaACwAE_BGoAC}@AKIuAIoAAKSiCGq@?AI}@OsAQsAk@_Eq@wD_@gB_@_BMe@?Ck@qBuByHq@aCcAiD{@_DsAsEcAqDa@yAy@_D]}Ai@mCUsASwAYsBIo@I{@K_AGq@IaAEg@Ce@Ce@IwACo@G_BEuBCkB?kC@cC?oB?a@Bed@?g@?uO@mB?wF?oL?qG?uB?mA@y@?K?Q?S?oF?o@?oE@mH?cLQ_HSaHIkAIcA?IAYAICW[gD[gCg@eDG_@o@gDc@uBa@eBYiAa@yAUw@So@i@cBe@qAWu@g@oAcAaCWm@[m@e@_Ac@{@Q[OY}@{AOWYc@Ye@yA{BEIAAeA_B_CoDuAwBo@cA{BkD_@k@]k@yA{Bi@w@?Ag@u@gCyDkByCwA}BaTc\\AAg@y@aBiC[e@o@cAMSm@gAa@}@]s@m@{Ai@{AOc@So@Uy@[mAYqAQaAO}@Oy@OoAMaAKsAIw@E}@GgAEyAC{@AkA?KCyAAyAAuAEmDEmFEmCAiAAaBAwAA[I}HMcMEcEAoBCqBC}AI_H?EIeH?a@CeCAk@CkDEgFGqFEcDC{CA}@A[?cAKyIAoAMiKE{EIcIAoACcACyDIuIAo@GyGE{D?CE{DCoCAMAu@Ak@C_@Ae@AIEsAIqAE}@Eg@IgAGu@Gu@OuAKaAK}@Gg@QmAGc@Ga@QgACMWuA[_BScA[sA]sA_@wAa@yAUs@_@gAUu@_@cAc@iAa@cAe@kAi@gAs@}AeA{BsAsCoAqCkDoHUg@iSac@Se@wAyCcCoFgWmj@gRka@g@gAkBaEmWoj@wGsNeGuM{Rkb@Sc@oGgNSe@eHkOSe@]s@cAcCEIKYKWSk@[_A]eAIWM_@_@oA]oA_@uAa@kBYoAWkAOs@SeAMw@Ik@SkAOeAQqAGk@KcAIs@AKKiAEa@Ek@Eu@AKEu@GeAGiAAWAk@GyBAM?OAYA{@Ay@AqB@wG@uEBgEBqGBeI@gC@oJBsLFwb@?WDsS?o@@aD?q@BiIBmR?g@@}FDiQFgX@aG?yAD{T@wD@kHB}M@oC@{D@wC?m@?oC@aE@oB?_C@iD@yC?K?eC@q@@iH@eG@uC?M@}@?_@BkF@ySBmN?wB?C@_@?C@aC?eDDmN@yE@kFD_VBiJ?}@DyS?e@?WAWAk@A}@Aa@Cy@Co@C[?OC[G_AC[ASGo@Gq@C_@E]QsAAKCOE[Ko@EYMs@g@mCGWYgAw@sCIYIYM_@Oc@M]eAkCEIEMMWO[IQMW_@s@cAgBMSGKGIm@}@o@}@SWKOUWm@s@{EyFY_@qGuHY]]_@g@o@c@g@_@c@EG_@c@g@o@_@a@cAmAoCcDsDkEuDoEeFeG{AgBa@g@CCSUYa@KKk@w@a@m@Wa@S[eAkBIOEKOYc@}@EMEIg@kAi@uAi@}A_@mAUy@Me@ESEMAEAGe@uBG[YyAEU?AAIQgAQyACOCOKkAEg@Ee@IgA{@{K_@gF?GKeAAUSoCGs@SiCMkBKuA]mE{@cL[gE[mE}@mLMoB_@}EIeAMqAMqAGe@QqAMy@Km@G_@Q{@EYOs@Oq@EQGUCKEKK_@Qk@GWW{@Y}@a@gAi@uASi@q@wAmBwDu@yAKScDoGuC{FyCcG{@aBAAUc@kLiUyAuCoAeCuAoCg@aAo@kAYc@Wc@cAwAo@{@c@i@OOq@u@iBiB_@[_@[{@m@aAs@a@Ww@c@k@[e@Wi@Ui@Ui@Ui@Qk@Sc@MCAa@MWGcMcD{Bg@qBg@{Bk@kBe@kCq@a@KgBc@gBe@eD}@yD{@qFuAsEkAuA_@sD_AyCu@CAYIo@OsA]{A_@u@OSEqAWq@K{@M}BUyAKA?sAI{AEC?c@A{HCoTGsDAsDAYAoJCsDCcA@eA?sDCM?cGEs@Ac@EmAKUCg@G[Ec@G]GA?]IgBg@[IGC_AWWKe@Qi@Ug@Sk@Y_@S}@g@eAo@k@a@a@]}@u@e@a@aA}@a@c@a@c@m@u@[_@QW}A_Ck@{@m@iAeAiBAAUe@i@cAiBeDmA{BwLuTWc@wGyLUc@yWaf@S]MUSc@{DkHwCoFgCwEm@iAq@kAo@mAqJgQqJgQ_OiXq@kAyAoCoEgIiJ{Pu@wAOQMQQYK[KYOWYg@q@oAgQw[We@qEiIUc@sBwDWe@qEiI{AqCWe@qAeCaD_G_BwCyAmC{@}AYe@e@}@_AcBUa@wByDU]Ye@w@sA_A{Ai@y@_@m@uCsEoIaMmBuCm@w@}FsIWa@{EeHWe@gHcKuDsFqJqN{@kA_AuAg@q@{BiDw@gAiEmGqGoJcEaGcHaJaDwDaA}@{@}@aAaAe@c@eAaAg@g@uBiByAmAmCuB[UYS}@o@mA}@iAy@}B{AeGiEg@c@q@e@wB{Ak@a@{AqAeA{@u@s@g@g@_AaAi@m@Y]e@i@i@q@o@w@i@s@mA}AMQcAoA_AkAwBaCaAcAyAuAgB{AKIwAiA]WIEiD_CoA_A_CcB}AgAcAs@}@k@u@i@GEc@[WQQMQM{@k@qAaAqCqBa@Wk@]m@_@sGyEEEsCuBuB}AEA]Y_@WmA}@cH}EoDcCiHaFoA{@wCwBkFqDCAcEwCcDcC_BqAo@k@[WkDaDcAcAoAqAaAeAOQ_CiCyCsDkA}AgA{Ao@_Au@gAi@w@cBkC]k@]o@aAaBeAkBWc@e@{@GM{AyCuAuCgDiHgDgH{A_DWi@{AaDaAsBmEiJqHyOcCeFoBiEs@wAmCyFoEmJwD_IcCkFcAuBuE{J]s@kAcC}@mBWi@qAmC{A_DO[k@kAUg@CGwAwCiByDi@kAwBsEgBwD}AiDgA}Bk@kAsBgEKWMYUg@Wi@q@{A_@{@Ue@q@{AsAuCmCuF]q@aBkDuAuC_AuB_BkDoAmCmAiCgAaCa@}@qAsCaAqBc@cAcAyBa@{@Yo@u@_BkAgC_AwB[o@e@eAg@eAuGyNuAwC{@iBEIwA}CsBoEuOa]yTgf@}BcFcEaJeGwMeCoFIUA?Se@_CiFUe@w@eB{DoIyB{EoBkEkAgC_CcFc@_Aa@u@g@{@[g@qAsBg@m@{@gAq@y@CCcBcBa@YiCqB_E_Ce@Ua@Qe@Q]MYKc@Oi@O]Ke@Ks@Qo@MYG[E[G]E[EYEg@Ec@EC?UC]Ai@Ca@AgFAo@?W?iA?iBAc@?eAAA?c@AiBAc@?kBAsDAc@?oCAqAAqAAoAAoA?{FCqCCi@A_@?_@Ae@CE?u@EiBSKAMCyAYa@Iq@Qi@Om@Sq@Uo@Wc@Qm@Wg@WYOa@UWM]Ue@YYSi@a@g@_@]W}AoA{BqBgEkDsAgAiCyBuD}C{BoBeByAaAy@mB{AcByAwCeCcMkKu@q@o@i@aA}@i@e@wAmA}F}EoBaBsDaDiCqBs@k@s@k@q@k@gDyCcDqCiB}AoAeAcn@sh@i@c@_FcEmEuD}DgDw@q@wDaDuAiAw@m@e@_@o@c@k@]o@]q@_@eBw@?AiAc@mAa@o@Q]IICaASoAUkAOw@I_@Cu@E_@Ai@CoAAcA?}@Bs@BQ@G@]Bk@D[DYD[DWDWDu@PcCj@IBiCn@kCr@E@oA\\u@PsAZsAZiCp@E@kATk@F]DI@o@DI?YBw@B}A?gAEcAIc@Gu@Ms@MEAo@MkAa@mAe@kAm@_By@_CqAi@[{A{@}@e@}@g@kAs@SIo@_@{A{@}EoCy@c@}DyBaBaAoAq@oAs@}CeBcH_E_@SaDgB_Ai@g@Wy@c@k@]uAu@_@UaAi@_Ai@_Ai@_@Sa@UaCqAoBgAqAu@{A{@yAy@[QyCaBuCaBuC_ByBmAaDiBaCsA_B}@kAq@wBkA_CsAa@S_@S_Ai@aAi@_@U_@S_@UKESMa@U_Ai@iBcAWOcB_A]S]Sa@UKEqC}AyDwB_CsAqAs@mDqBkGkDuBkA{@e@_B_AIEAAaAi@_@S_B_ASKgDkBGE_Ai@aB}@{@e@CCk@[cE_CiE_CeE_CcBaAiCwAe@YsAq@gAk@gAg@s@]wAk@GEUIqAg@oAg@cBm@gBo@qAa@q@SgGcBaCk@iCu@qEiAaDy@iEkAs@ScFsAuEmA_Dy@aKmCa@KgBe@a@MeAYa@Kc@KMESEc@KcBe@kBe@a@KkBg@{DcAiBg@gFuA{DcAwDcAoEkAgKmCmFsAs@SmEmA_Dw@_AWwBm@gFgAkB[{AUoBSwBQAA}AOGA{CKmCEiCAyD?eAAoAAcD?cC?mCAgAAqB?qAAu@Gw@GQCEA]E[G[GMEKCq@Sw@WSI_@Om@[c@UaAo@k@c@k@g@cAeA_@a@_@g@a@k@g@w@[k@[k@e@_AWo@IQc@cAiAkCqA}Ca@_AaA{BwAeDsBaFIOeB_EoBwEQc@eD}H]y@gCaGUe@}@uBcFqL}AgDc@}@CEe@aAiBgDy@yAWc@Uc@oBmDOWS[[k@i@cAo@iAIM]k@s@oAcB_Dm@iAaDmF_D_FwDmFk@y@yAiBY]w@_Au@}@[]SWoDcE}DuEkFeGaHcIiFaGiGkHuH{IyAeBoAyAeCuCa@e@g@i@sCgDQWUW[a@U]UY[i@[e@Q[KQKSKQIQQ]S[O[Wk@[w@Q]Oc@Uk@KWIUQg@Ss@M_@IWOm@Ma@Ok@UcAKg@G[Mo@Os@Ie@EYKw@M_A]eCs@uFS}AWiBMcA]iC]mCM}@_AoHeAcIQkAOkAqDeYIm@Ig@q@oFIm@kBgNc@mDESgBcNMiAs@gFg@yDg@yDq@_FQyA?CCOScBY{BYmBY_Bi@oCS_AYkA[uAKc@YeA{@sC[aAUs@a@kA_@aASg@M]cBiEk@wAw@iBuAkDeBiESg@eBgEgLiYcBgEmCyGcEgKs@eBe@gAACc@cA{@aCe@oAyCkHqAcDaE}J}@wB[u@kDwIs@aBqO_`@aAaCcAcCi@kAYm@Ue@e@}@e@}@_A}AeAeBeA_BiBcCuBcC{B}B{AsAWU_@Y{@m@sDiCSMm@]kAo@yDsBsFyCiOeIeBcAmBaAiJcFuEeCaG}Ca@SgEaCuBiAiGeDmBeAea@mTc@Ui@[eHwDi_@iSmAo@SMc@WsNwHyZoPOKcB}@_Ak@_Am@m@a@WSyAiAqAgAa@a@s@q@a@_@SW[_@wB_C[c@cAqAeA{Ay@oA_A}Ay@uAq@kAKQw@uAi@}@_@o@ACq@gAuFwJiCoEsA{BO[gImNCEi@_Ac@u@uAgCyAiCWc@o@gAoAyB"
                     },
                     "start_location" : {
                        "lat" : 41.5846019,
                        "lng" : -87.23498309999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "53.9 mi",
                        "value" : 86747
                     },
                     "duration" : {
                        "text" : "47 mins",
                        "value" : 2830
                     },
                     "end_location" : {
                        "lat" : 42.2814084,
                        "lng" : -85.38109609999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork to stay on \u003cb\u003eI-94 E\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "ehc`GlkenOmBcDiJ}O_A_B_@o@iB}CS_@_CgECEwBsDoB}CqBuCqCgEqEuGw@kAqC}D[e@eCwDYa@qC}DyAwBw@oAWa@aDsFkC{E}CuFgEyHyAgC_BoCiAkBkDoF}DgGkAkBkAeB_EoGwBgDGMm@_A_B_CgEwGaAwA_CsDmAiB}AaCqAoBa@o@kDkFqCiEiDkF_AyAe@w@IKYc@sCgE_CgDGIgBcCgAyAo@{@yByCuCwDo@{@_BwBwC{DiA{AkBeCsAeByEoGeEsFsBoCgB}BgAyAgBaCqAcBs@_AQWeB}B{AoBmA_BaBwBs@_AuAkB_@e@eB}BW]SWiAeBs@iAw@uA}@}Au@{Am@qAg@mAWm@w@qBu@uBQk@Sq@e@{A]qAACYiAm@_C]gBWuA_@yBQiAQiAM_AK{@QgBOqAKmAGiAIoAE_AE{@Cc@Ck@CcAE{AE_B?KEaAOcISsIMcFKuGSiJEgBKiEIyCKyE?WIiDK}DE_BAm@?A?QAK?UAWMuFUkLMaFIyDAc@I{D?EGaDA_@IaEGkCAKAo@GgCYcNGoCAo@GqCOaHCo@a@sRIaEMoFAq@KwEKqEA_@GmCS_KQgICeAEsBEsBQ_IMqFMmFAiACuAIiDAi@WgLOiHIcDCqBKeEAo@EiBCo@?QEiBEiB?CEsACy@CaAGcBIgBGkAEcAEw@MoBKeBG{@Iy@IgAMwA?CM{AWeCK{@Go@Iq@MeAKy@Iu@UcBq@aF_@oCy@gGYsBE[QuAgAmIk@eE{AgLgA_Ic@iDw@{FoAmJIq@Gc@My@s@mFs@mFk@iECQQkAqBkOw@cGa@wCo@}E_@oC_AgHe@eDSaBAIm@qEQmAOiAe@mDOkAWkBg@uD]eCOiAIo@AOM_ASaBQwAQwAUsBMkA]_De@uEk@qGQuBKsAMwAEo@IaAG_A?AUgDO_CGaAKmBOoCYkFu@eNe@}IOkC?A?GKeBS{D[mFEw@Co@e@mIkBi]GmAkBk]?K]iGOmCOmCQuDM_DEcAGeAYiJKsDAg@UmHKiEEqAMoEGeCSwGYgKm@_TG}BGyBCwAAg@Cy@CgAEkDCaBCiA?i@AY?o@AK?aAAw@?KAoA?eAAwAAmE@mD?}B@sF?mH@uB?wC@sD?}C@cEBqX?q@@mF?eE@{D?eC@}C?A?cH@sH@_H@wD?gB@iG?aB?aAAo@?s@Am@Aw@Cu@C{@Ae@A]GuAE}@Ca@G_AIiAM{AMwAQ}AMmASyAM}@QgAMw@YeBQaAESMm@Y_B}@}EG]QcA[eB]iBmBmK[cBUoA[eB_@}B[_CQsAQgBQ_BKyAGu@AQAKE{@CWEu@AS?QGsAGaBAi@?UA_@A_AAy@?oA?y@?_A?cA@aA@oB@iBDaG@k@?[FcKBeGFeKVwd@FwIDsHBqDT{c@BmF@m@BaERo^D_HHiLDiI@qBJuPFmLFsKHyL@k@@w@?MBmD@gE?Q@sCByBDsF@yADwJ@a@@yGBeCB_D?o@@kBH_J@wCDaG@mADuADyAB}@@[Dm@FqAJ_BNsBNiBD_@TuB\\cCZwBb@uCPgAbByK@EzByNv@aFbAwGLy@|AaKl@oDZuBlEeYf@sC~BmOn@wEb@iEZiEPgDHcCHeCDoGCgEGmCK_DQ}DOsBQqBI{@OuA[kCMu@YsBW_Bm@yCo@cDw@}Do@iDWuAcAeFoAoGcE}SsAsGeBeJoCkNWqAoAwGSaA_@iBc@_Ck@wCg@eCoAkGs@wDGYI_@sCeOsCsNQ{@Mk@Ic@]cBG]o@{C{BqLMk@[_BaAcFSeAi@mCy@gEoAuGoB{JA?_DoPuC_Oc@kCIi@QsAY{BSmBUiCSoCIyAEq@Cu@EoACkAEsBAwAAcC?gE?_F?mC?oB?}I?wG?{]?oB?uF?o@?}D?uD?mCAoECoECyCEmDOsJGwEIuFOiKKyGIcGEoCK{GG}ECyAGuDEqCEyDEqCCsA?UEuBAw@Ao@AgAG}DG{DCgBCkAAoACoBCmBEeBCqBEkBCsCEaCGcEAuAEaCEgCG}DC}AG}EGyEG}DEuCCkA[kT?CAk@AOAm@?AGmBEiAIoBIkACg@Ca@Ea@Cc@KiAKeAIm@E_@Ee@QmAS_BQiAY_BKk@UgAYwAKg@Ka@Mg@G[K]I[Mi@W}@[cAY_Am@oBoCoIw@aCUu@cCsHq@sBeAaDu@}Be@yAOe@Oe@Yy@eA}Cg@}A_AyCi@aBcA}Cw@aCcAaD{@iCuBuGeBoFc@qAg@}Ak@eBc@yAMa@YeAc@cB[sAWoAUgA]kBYgBa@mC[mCYoCUqCQqCEkAKoCEgAKkCIwBQ}EKgDE_AUyGQ_FEiAEkAIoCIoBCu@GaBKiCMuDGcBOmEOyEO{DMyDKsCAOG}AGoBEaAIwBAi@GiBKqCI{BGoAAm@IkBK}CIsCIkBGqBGkBIoBGsACaACe@EiAIwBGeB?AG{A?YCk@?CKqCAKAc@KuCGoBKqCKsCCw@AOIqBIoCIqB?MEy@EgAIsCKsCImBEoACw@KyCG{AE_BAIOaEM_EGuA?WK{BQmFCq@K}COkEM{CAc@AYC}@G_BGeBEw@Cy@Co@GgBKyCSyFm@oQKyCQkEK}CEuAMiDo@yQg@aOCo@Cm@E{AEwBCuA?GAi@CoA?_AAeAAeA?cBAmC?iC?wC?aA?w@AiF?cDA}G?M?_@?QAyF?U?mAAyLAaGCiJ?gH?eAA}B?{B?yC?oA?WAsE?m@Ey]?o@?m@?oBAyB?o@?gA?yD?CAsCA{H?gM?o@Ay@?eHAeC?sBAeG?KAcK?o@?sFAiDAgA?iBA{@A{@Ac@C]C{@CcACcAEs@I}AGkACUCWEm@MuAWeCIm@Gg@QoAIq@EYEUIi@O{@Ic@Ki@Ow@GUUgAWgAYmAQs@Su@Ok@Qg@_@sAQm@m@kB_@oAmBoGaBmF{A{EqAiEQm@GSA?e@}AyCsJwBaHI[cAcDeAmDgAkDc@wAwBeHOi@kCsIQk@Qi@gB}FOk@iB}FOi@mAyDyEwOeAiDwAsESo@AEW{@c@}AOg@Sw@Qu@Mi@Ke@I_@EQEQMm@Ow@Ki@Ms@Ic@AEG_@Ks@Kw@Ig@E_@Io@G_@C[Gc@Gi@Cc@Iw@Eg@Ea@Ee@Cc@AMCk@Ee@Ac@C[Aa@Ca@Ca@A_@Cm@C{@Aw@CuAA{@?q@?eAAi@?e@@sD@}J?eF@wC?}D?uC@sB?qB?oB?{A?u@?_B@qB?sC@wA?{A@w[?o@@uE?_FBo]@gL?o@AcBAkF?o@?_BCcHCqHAkA?c@AuCAqBCaGAsDAmB?cAGaQAo@GwREqFCqGCyEEqGCkI?q@CqGEwGAq@CwH?iA?w@?CAqB@{B?}C?kACqD@aB@aBDkW@eKHuN@}Q@yD?iF@}D?cG?iG?mG@eABoK?gG@O?uE?oF@sF@aF@kE@aG@O?q@BeK?iAD{EHuGD_@?o@HiFNqIFeBTeIPqFFaBBo@JgDN}ELsDHqCDw@NmFBm@@S?W@c@HqBF}BDaBBu@BsC@yA?aC?kACuA?YGqCGuBE{@E}@ScDMmBAIUgCSkB_@qCUiBa@gCUoAWsAa@qB[sAEQm@cCIYMc@Sq@IWI[g@}A_@iAWw@yAcEUm@m@aBYu@_@gAy@yBCIu@sBi@wAmA{CqAqDoAiDwAsDo@mBWw@gAqDIYaAkDU{@[mA[oAEM{AgGa@kB[mASu@}AiGeCuJ{@qDQs@iBcHo@kCa@_BsAiFq@qCoB{HSy@K_@{AcGiAqECI?Cc@gBWeAOi@Mi@U_Ac@aBIWOk@e@}AOe@Sk@Wu@Oc@k@yAGQQa@AG_@y@_@{@O]c@_Ac@{@u@uA{AiCKQCCkAkBaAyAu@kAkAiB{@sAy@qAaCsDkBuCc@s@eC{D{F}IwAyBw@mAoCiEIKqAsBu@kA_BgCw@uAqBgDOUg@_Aq@kAa@s@mA}Ba@u@Q[Q[uFoKy@aBcAmB?AuFmKg@}@?ACEiAwBs@uAq@uAQ[Qa@Ug@Wo@]_Ak@cBWw@GYOk@I[]yAMm@Q}@EYE[UwAKaAGk@KcAEe@Cc@IkAEgACi@CiACqCAuB?YGsTCoECkHAeE?_@Ao@CqI?AC_G?c@?C?IAyE?aBCkHC{FAwBCoCAoAEgBA_@IkDEuAImBIsBGkASaEQqDSyDUqEGeAUsFG_BEaAKyDEuBIoEAqC?[?UAcC?qB@gBBeCBgCLgGTeHPcFRwGHmBHkCFaBTwGN_ENuELwDRcFN{EPwELaEL}DFyBB_BBqBBeABgC@_BBaC?{B?wB?mDEyEGaEG}CIsDI}BC_AMyCKqBMqCKgBQuCQsCOoBMaBKmAY{CWgCYqCYiC]qC_@mC]mCi@kD_@cCESIg@e@kC]iBQcAIi@w@kEq@yDs@}DUwAQ_As@}DW}AMu@Ms@Ku@O}@UaBAMO_ASaBMsACWEUKcAOgBU_C]qDM{Ae@kFgAaLuAiOGo@SuBYgD_B}PsB{TAKKqAg@kFu@iI{@cJu@eIkBoS?CEc@AG]}D]gDg@{Fa@mEWeCUiCk@cGa@oEWqCEa@AG?EGi@QqBKkA_@_EO_BKiAY_D?AE_@[sDIgASsCO{BSeDGyAGoAOiDQeFASAQ"
                     },
                     "start_location" : {
                        "lat" : 42.1288312,
                        "lng" : -86.37639159999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "20.1 mi",
                        "value" : 32307
                     },
                     "duration" : {
                        "text" : "17 mins",
                        "value" : 1047
                     },
                     "end_location" : {
                        "lat" : 42.2972608,
                        "lng" : -85.0059263
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eI-94 E\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "yaaaGz~bhOUmJOqFSiIEgACwAAIAe@Ao@GmBGsB?QCw@KyEQaGG{BAg@?]E}@AiACeBCiBAyBAcB?a@?_AAsBAoD?aCA_DAsAAcKAq@?}BAsB?aB?o@AoEAcC?yCA{GAo@?_A?c@?m@Ao@?oAAwEA}E?{C?sB@kA?s@B}@@s@By@Bw@FyABy@FiAJsAHgADm@HaALgAJgA@GFk@PaBFg@b@cEVwBD_@b@yDDe@LgABQPcBFm@Fc@RiBBW@MRkBFi@TwBBSn@}F@GJgATqBPaB\\wCNqAXqCb@wDBWFm@NiARqBBYDUN}ADWJgABUBWHm@~BkTt@yGBWHo@BWNqA@KTsBBWZmCP}ABWf@sEf@sEBWBUBWZmCFo@BUn@cGt@yGvAuMt@{Gt@yGl@wFpBwQjB_QLiA~D{^hAmK@M^gDr@mG@MD_@b@}Dh@{E~@oID_@Ho@BWBWReBXmCb@yD?C`@yD?AV}BpAsL@CXqCx@sHjAuKD[zEoc@ReB|@iIxBgSrAsLfBgPLgAT{B\\oD\\_ET}CN_CL_CX}FHcCFoBBuAHsDDsD@gA@oB?wD?k@@gK?kD?K?g@@yF?eL?g@?_ABgQ@uQ@kG?qFBaZAg@@e@A]@gF@kB?GD}D@oABqADwA@aA?W@M@UBi@N_EHiBR_EJkBr@_Mt@uM\\yG`@gHLqBFk@XcFb@{HrC}g@h@iJRwDXaFXyEJiBD_AFkADuADaB?IBeC?_B?cBCgCAsAEkBCe@G}AW{EUuC_@sDASIg@OiAq@oEc@gC_@gBc@mBWcAQq@c@_Bg@aBY_ASg@g@wAiBqEkBcEsGsM_EeIiBqDYm@sCyFqEeJmMsWSa@a@{@kAaCeAwB_@w@_@y@oFqKmCoFmGcMkA_CKS}AcDWg@m@kA}DiIoGmMuBeEUe@iCkF_@s@_@u@k@kAuA{CO]]_As@mBGOa@qAY_A[kAI]K_@ACKc@[qAUcASgAYaBWcBGa@[mCQiBKwAIcAAOGuAAUCm@IkDI}B]{MUsI?GAGAg@?GIiCKcEG}BIeCIqDCk@C{AKsCIqCEiBE_BQyGa@yNOmGIyCKyDCo@Cw@Cy@A_@GgBEw@C_@KgB?IC]KyASsBE_@IcAOgAK_ACMM}@CKYkBEYG_@UiAg@iCk@eCc@eBo@{BOe@GUQi@Uy@g@_BGO]gAg@aBaAaDiG_Ss@_C{@oCiAuDeAkDUw@Qi@]eAm@qBqAeEuAsEQk@Ww@Ka@aA_DACQm@Qo@W}@YeA}@oDQy@Sy@AGUcAU}@UkAe@_Ca@sBMk@u@{DeJce@cAkFe@aCOs@WqAScA_@oBY{ASiAc@sCKm@MiAQyAEe@Gi@Gu@Em@C_@Cc@ImAEcACgACe@?C?_@CgAAg@?a@?e@?e@?i@@oA?cA@_@Bu@Bw@?SBo@@WDo@Bc@Be@Ba@@SBWD_@B_@@OD_@HeAp@cHt@kIvAmO\\gDL}A@KP}BNeBDm@B_@@M@WB_@F_ABc@@MFcABe@Bg@@_@B[Bs@Be@Bw@Bs@DkA@e@@g@@UBiA@m@@c@@eAB}A@u@@eA@kA@sC@mI@{FD{a@Hwi@?uB?o@Jwt@@qG@uJ@sA?[?q@Fub@B}N@qH?}E@wD@_F?wD@oC?oB@wDBeO@aG?{E@{D@uC?kC@cABiK"
                     },
                     "start_location" : {
                        "lat" : 42.2814084,
                        "lng" : -85.38109609999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 278
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 42.29708290000001,
                        "lng" : -85.0025672
                     },
                     "html_instructions" : "Take exit \u003cb\u003e108\u003c/b\u003e for \u003cb\u003eInterstate 69\u003c/b\u003e toward \u003cb\u003eFt Wayne\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eLansing\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "{ddaG`vyeOBM@G@G@I?K@M?WDeDBgD@YJ}E"
                     },
                     "start_location" : {
                        "lat" : 42.2972608,
                        "lng" : -85.0059263
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "41.0 mi",
                        "value" : 66000
                     },
                     "duration" : {
                        "text" : "36 mins",
                        "value" : 2161
                     },
                     "end_location" : {
                        "lat" : 42.7716955,
                        "lng" : -84.66901059999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork, follow signs for \u003cb\u003eI-69 N\u003c/b\u003e and merge onto \u003cb\u003eI-69 N\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "wcdaG`ayeO@aABaG?kG?aB?mE?I@G?I@G?eC@q@?yA?s@@oA?I@E?E?G@]@c@?O@K?IBM@OBKBGBK@C@EDIDIBE@CDGDEDEBCHGDCFEHEFAFCHAJALAH?H@D@HBJBJFFBDDDDFDHJFJDHDJDHBH@FBH@HBJ@L@L?J?J?NAL?JCJALCJCJCJCD?@EJGHEFGHGFGFIFGBKFG@E@GBI?E@G?I?IA_@AE?E?I@a@Gk@GEAc@Eq@GA?_@EC?SAUA_@EE@A?C?E?EAOA{@IiAMi@EeAKiCQc@Eq@E_CQoCU{Fa@wHi@C?E?G@K?ODcE_@o@GwD_@iCUUCKAsBQkKcAyKeAkAKcCU{BSiBSoEa@_Fe@sCWkEa@iCSEAYAaCW_AKkCWmBUOCcBUqASoASkB_@qAYkBc@sA_@u@UqAa@kA_@mAc@qAg@kAe@}Aq@[M]QCAs@[gB}@iAm@aB}@mAu@w@g@uA}@s@e@k@]sA}@}DiC_BeA{CqBgD{B{E_DwBsAgBcAmAq@cBy@iAi@s@[_A_@eAa@YIgBm@wAc@o@Ou@QoAYeB_@qB]oB[mAMc@Gy@Gs@I}@EwAGa@Au@Ao@Cq@AqA?o@?eC?cD?iC?sAAiBA{@C]?O?qO?qICaFAcA?cLC{ICm@?_AA_AAmBE[AYAc@CSAw@Gs@Eo@GGAGAo@G]EKAOCg@Gg@Im@IsAWgASUESEICu@SSE_@Km@Qa@Mk@QYI{Bu@a@M]MUKq@WYMs@[u@_@eBw@WOWMa@Sm@_@sAy@YSm@_@UQ}@m@g@_@s@k@yAkAgA_A][g@a@qBeBcDoC{AsAqBeBeDqCuD_DwAoAc@_@c@]aA{@eA{@a@[e@[a@[e@[e@]]Sk@_@i@[yAy@a@Wi@WUM]OAAa@Sg@UYMQIa@QOGMGSIMEg@Sc@Q]Me@Oy@Wm@Sk@QMC_AWq@Ok@Oa@Ik@M{@Og@Kg@Ia@Gk@Ig@Ii@Gw@IUC]Em@Ee@E_DOq@Ce@AmAC}@?aB?aA@oABsADwAHm@DSBI?A?]DU@y@JgALoBVuANaALuDd@kGr@{BXyHz@qBVoCZkALYBa@Dq@Fe@Dk@De@BY@YBm@Be@Bk@@]@]@u@@}@?O?uA?cDEe@CUAmAGwBO]Cc@E_@CaAKm@Go@Iu@KuAUq@Ki@KaASa@KqA[eBc@g@MgCw@i@Qk@SQGUIcAa@mAg@[OUKkAi@cBy@u@a@c@WsAw@kAs@GE_@U_@Wk@a@OIMKc@[c@[e@_@a@[cAy@aCoBiAaA]YaAw@aDmCk@g@SOgB{AQMgA{@CA_@[YSiCkBqBqAc@Ym@a@]Uc@W}@g@eAm@e@We@Uw@a@}C{AaAa@wCmAoAg@aEuAg@Q[KGCa@K}@We@Mg@OeAWq@Oq@QkDu@gFiAkBa@a@I{@SsCm@i@Me@KoBa@_Ds@ySsE{@Q_TuEk@Mq@OEAEAQE]IYIu@Sa@IaB_@yCm@aDo@mBa@cAUaE}@e@KqA[mA]gA]g@Ss@UqAi@i@W}@c@_Ae@u@a@{@g@g@[k@_@UOm@c@WQe@]a@[k@c@SSKIA?OOOMa@_@a@a@YWWYMMKKa@c@e@i@UY[]AAa@g@QUa@i@Y_@m@{@S[a@m@_A{A_@q@e@y@_@u@c@{@]q@CIa@y@a@}@KYM[Qa@Oa@]}@Wu@]_A_@eAe@{Ae@gBc@_BI[UiAUaAi@uC}@qFWiBi@wDu@iFCUu@aFg@qDe@kDE[s@}E{Ea]oA}IIk@y@wFQoAGe@{@_GGc@_@qCWcBa@wCoAyIg@qDa@uCWeBm@iEg@mDa@qCM}@AG[{BUyA[gBg@gCWgAUaAc@cBU_A[cAUy@]eAYy@_@eA[}@_@}@IQSi@oAqCUe@a@w@o@oAe@w@u@sAu@oA{AmCuA_C}@yAaAgB{@uAGM[i@kBeDq@mA_@q@y@yA_@s@MUe@{@Yi@cAmBs@wAc@}@OYcAuBq@wAo@sAc@_A]u@a@_AWi@GM}@qBaA{B_A{B_AuB_@{@Ug@i@mA?CaAwBkAmCM]Ue@{@iBWe@eBiDkAqBu@qAu@kAU]iAcBqAiB{@kAy@cAaAkAsA}AaAeA_AaA_A_Ak@i@gAeAgAgAgAeAcB_B[[iDeDwAwAkBmBkBqBuCcDuAaBi@o@uBiCeB{BeB_C[c@sBuCu@iAeCqDoBoCcC}CKMqB_C}BeC_@_@y@u@i@g@{AuAkCuB}@q@w@m@m@a@q@e@eDuBcBeA_Ak@sAy@}DgCyBsAmCkBaBqA_Ay@_@[{@y@sAuAk@m@{@eAq@{@g@o@s@aA}@uAm@_AaAcB_@q@i@aAiA_Cs@_Bg@oAc@eAYy@_@cAk@aBoAuDOe@CEuAaEu@uBgBuEaA{Ba@_AYq@a@}@o@sAw@_Be@_A[m@uAmCgAoBe@w@cAaBm@aAeAcBi@u@mAiB}AyBQUgBgCoAeBy@iAoAeBkAcBa@i@yBcDwAwB}BoD{BoDOYyCaFuC{EiDwFIMiCmEw@oAuA_C_A}AgAgBw@oAoBeDWc@k@_AsAoB_BuBa@i@iAsAsAuAm@m@i@g@cB{Ac@]m@e@eAw@{@o@e@YkAs@eB_AcBy@c@S_A_@m@Uy@YqAc@mA]iAY]Gs@Oq@M}@O_AOgAMYCm@EuAKs@Ew@Ce@AU?u@AmB?sA?oA?mB?s@As@?]@oA?}AAkA?aC?aA?M?a@?y@@qAAw@?mA?sA?w@?aC?gB?qB?W?wA?aE?cC?yB?eB?iA?}A?sL?}I?aE@yBAuD@}C?C?g@As@?_B@yA?oCAE?qB?wA@uCAUAwA@e@?K?g@?G@aCA}B@uBAqB@q@AoB?}@@kBAiC?qA?}A@_@?aCAgA@sA?iC?}A?kDAuA@qB?aAAs@@wA?{A?[Ae@Co@C_@Co@G]Eq@I_@Gu@Mo@Mo@MgAUkBa@gB]y@QWGa@IqAYoAWUGGAeCi@eCg@A?}Dy@_B]yAYWG_B]aB_@y@WyAe@oAg@{@_@m@YqAs@u@c@{AeAYSWS]Uq@i@eA}@aA_Ak@k@m@o@oAyAm@w@c@m@W_@e@s@c@s@c@s@Uc@s@qA]u@a@y@[u@Wm@c@gA]}@Yy@GS]gAY_A_@sA_@yAYqAe@}B]sBYkBOkAIy@MiAKiAKiAOkBEe@COS}BGy@MwAQoBM}Aa@sEGs@QwBMqAQoASyAM{@Kg@Kk@Ie@SaAU_AMe@c@cBg@qB[}@GQAAIQYs@Ug@Yo@_@y@kBsDg@aAQ]cAoBu@yAe@cA_AiB]q@Yi@iCgF_AgBGMgBoDgCcFeAqBUe@eBiDu@wASc@_@w@S_@[m@u@wAiA}BmAaC_FyJWe@{M{WqB}DUc@Q_@cC{EOWO[Wg@qCqFiA}Bk@oAe@gA[w@CE_@{@GQ{@{Bg@yA]eAWw@Yy@Wy@_AuCAGOc@Uu@kAmDi@{Aw@qBgAoCOa@_A_C]y@w@oBc@gAqAeD]_AgBmEe@mAWq@aAaCeDkI_@cAqAaDSi@gEsKoAaDmC{G]{@GOe@kAe@mAQc@Qe@a@cAg@qAMYM]g@kAu@oBwAoDYw@Se@u@kBmC}GEOw@oBs@eBUk@]}@Wq@Qc@kC{Gg@oA_A_C]{@Yu@e@gASi@iBwEQe@gCsG}B{F_C_G_AyBu@eBa@s@_AeBoAyBiAeBq@_AgA_Bc@g@i@o@o@s@o@s@m@m@MMaA_AsAiAOMgByAsFmEcCmB{@y@y@s@mAmAgBqBQS[]SYuAgBYa@_AsAi@{@u@qAu@qAaAmB[o@_B{Ca@{@m@mAOY]s@s@wAwAoCaAmBi@cA_@u@gBoDuAmCWe@MWAEEGcAqBMWs@uAgAuBkAaC]q@yGuMiCaFUe@GMKWAAMWACAAg@cAsAiCc@{@iBoDIOUc@}A_D}AyCmKmSk@eAUe@cC{ESa@iAyBk@eAg@_AaBcDiA}BsAiCcBaDs@sA_AmBc@y@CEQ_@e@_As@uAs@sAs@wA_B_Dk@eA[i@EIYe@sBaDi@{@wAiBuAeB{BeCWYu@u@]Y[YUUWUWSa@]y@o@IGc@]YSYSm@a@iAs@WQq@a@YOg@Y_@SAAa@QCCA?_@Q_@Qq@Ws@Y[Ma@Qg@Qk@Su@UEC[IsA_@cB_@WGa@Im@M{@Oa@Eu@Ku@Iw@IoAKsAIsACwECcB?k@?gB?sB?U?c@?yA?{B@K?m@?s@?c@?K?sA?{@?W?wE?k@?mE@sF@mC?}@@y@Ac@AUAKAG?a@COAMAWCYCIAm@G_AM_@G_AOc@Ia@Ig@KYGYIg@Ki@O_@MQEYIi@QQISGWKYMWK[OYMYOCAUMIEMGWOYOWMYQWOWQWQWQWOWSa@Yi@a@_Au@WSUSYWUUQQSQYYUUUWUUSWUWUYU[SUUYU[SYQWSYU[c@s@S[S_@OYEGMUc@y@[i@g@aAqAuCq@_BqAqDoAcDACUm@IWm@_BM]a@eAWs@Sk@c@kAAC]y@EKISM[AAOY?AMWQ]MSCEQ[S[U[UYOSACSWEEOQACSSSWEEQQKKi@e@u@k@y@i@iAi@gAc@gAa@}@Us@O[EYEYCYCI?OASAI?[A]?W?]@]@W@Y@YDUBE?[Dq@JYFYF]JYHWH[JYJYLULYL[PWNYPUPm@b@WRUPWTWRUTk@d@YTUPWTSPC@UPGDOJSPWNWPWNWLYNYL[La@NOFYH[JYFQFg@HWFO@SDe@FYB]BK?k@@i@?]?m@?i@AG?Q?M@Y@WF{CEg@A}IMkBEgLMcLQwJMs@AeIKoLQ{FImOUiBCiGIc@?{EGcAAeS[kKOcCEwEGo]i@mBA}KOoCCiGKqCEw@Ag@AE?c@AW?}DEgKOsDE_@?yDIS?iIMeBCC?kBCyBEW?E?eBCkCE_CCyAC[AsACkBCaLOi@?[?w@Cy@?cAA}A@qA@_@?q@?gA@q@@u@@}@@y@?M@a@?oABq@BiAD}@DaADq@D}AHgBJwAH{@FqCRoBLkAHsCVS@gEZI@sFb@qDXeAJcCNi@DgBNoBJaAHO@Q@"
                     },
                     "start_location" : {
                        "lat" : 42.29708290000001,
                        "lng" : -85.0025672
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "119 mi",
                        "value" : 192061
                     },
                     "duration" : {
                        "text" : "1 hour 41 mins",
                        "value" : 6058
                     },
                     "end_location" : {
                        "lat" : 42.9727029,
                        "lng" : -82.49704679999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork to continue on \u003cb\u003eI-69 E\u003c/b\u003e, follow signs for \u003cb\u003eFlint\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "cz`dGh|wcO_@Ga@Bo@Bk@@m@Dy@Du@DwBJG@kBJ_@@mAFoAFWBM?K@W@A?M?O@O?W?M?UAW?Q?MAQAQ?QAYA[AMAKAQAQAWCAAOAMACAMAKCWE[E[GA?SEMEUEWIWGMESGOEiA_@k@SAAe@O{@_@wAu@m@][Q]WWQw@i@SOo@i@q@o@e@a@_@_@WYa@c@cAkA}@mAg@s@}@oAUWMQOS{@iAsAgBaEoFgCeDm@y@wCeEYa@k@y@s@gAeA_Bm@aA_@k@i@_A}@_BuBuDcAwBg@_A_BgDaCiFaAsBCGuAwCgA}B{AeDMWy@gBeByD{A}C}@qB[q@Uc@aE{IoAmCiB}Dg@eAcCkF}FeMoFiLiFcLEIUe@yAaDoAkC}@oBiAcC?ASa@Q]O]O[Q_@Q_@O[O]Q_@Q_@O]Q_@IQSa@ACa@{@Wg@]w@MYO[O]Q_@Q_@Qa@O_@Qa@M_@M]M]K[Qi@Oe@Me@Oi@Mc@K_@Ke@K_@Ia@Ka@Ia@Kg@G]G]Ga@G_@Ie@AMEWGg@E_@Ge@E_@Ea@Ec@IiAEc@Ca@Cc@AM?EC_@C{@ACAk@AYAa@Ac@?Q?SAc@?YAOAyFAaJAqEIqZAuBAiGAyGAgNA_F?UCgHAaHCgEAoF?aB?q@?GCiFAuGAkDAsE@aB?eAAaBCiBAeACgAAWCq@Em@Cc@Cc@G}@Gq@Gw@KeAIq@Im@Gg@Ic@Mw@Km@?AQ_AQ{@UcA_@yAMg@Sw@Qg@Qi@?AWs@[{@Ys@_@}@q@yAw@{A{@yAwAuB_@i@_@e@g@m@wAaB_@c@kByBgAsAi@u@SYOSKQEGg@y@S[KQGKWe@GMcAqBq@aBy@yBm@iB]oAkA_FCKg@qCWeBk@uFQiCCaACe@GaDKqCIqDAGAc@Ak@EiAAeAs@sZGyBGaCQqHIyECo@?ECu@IaEE{ACw@UeKIeDC_BGqBEwACiAEuAEuBAg@Ay@C_BAgA?u@Ak@?yAAeR@yG?wE?cBAcE@aC?E?c@?E?{F?eJ?gT@yE?sE?oA?qD?mMAoL?{@?q@@i@?c@@]@a@@g@@[Be@@e@B]Dk@Do@Dg@D[D_@Dc@Fa@Dc@Hi@He@Jk@DSDUH]\\{ALc@@CPo@`@qAPi@\\_AJUL[`@{@`@w@Zk@^m@j@_A`@m@PU^g@\\_@b@c@`A}@LKZYn@c@vBaBzFoD\\UHG~BcBp@i@~@w@DEVUZ[lAiAv@{@jAsAvAgBhAaB|@mABG`@m@nAyBp@mADK`@w@r@uABE^}@\\u@dAoCj@cBd@sAPe@xAwEPi@zBeHlAwDx@iCh@qBVcARcATgANy@L{@RkALcALeAJgANkBNuBFeBB}@BwA?kA?m@?wBC_FGoRAyAC}FKg\\EsFIiGAi@Au@AYKiDQ{EM}CMqCWkFOyCKyBKuBEgBACCeACoACoACsAAuAAwB?_A?o@@_@?eABoA@mAB}ADgAD{ADkAHkBJkBJmBPqBNgBHeALgALkARkBPqAT}APeANcAZgBHg@VuAVqAbBiIf@eCp@_DZaB`@qBDMX{Af@aCDQJi@TeA\\aBZ}AZaBR_Af@aCZ_Bd@_C\\}ARcAZ_B~@oE@IZ_BLm@h@gCb@oBtCoNt@wD\\mBZkBLu@^uC\\gDRiBDi@BQVsELqBRaC@SDe@?KN{BBq@n@}JVgELsBHy@Di@JgAFc@?EJo@Fe@VcBN}@Lq@VkAFYRw@Li@V{@d@_Bj@gBf@sAb@eA`@aA^s@j@eAn@mAtAyBhByCFKfAgBpAwB|AeCz@wA`@s@Zi@d@s@Zg@xAaCh@}@nBaDz@wA`DgFhAmBb@w@t@sAf@aAZo@FKLYb@}@v@cB`@_An@}Al@_Bj@}ANc@Zy@HYNc@J[n@sBp@aCf@iB^_Br@_D`AaFj@eD`@qC\\aCToBZ{Cf@aGPqCD}@JaCDaAFaBBq@@YDmB?ABkB?O@wA?M?cCAaCCoCAaAAi@CiAK{DI{BMqFAKO}FIiCEgAIwAE}@IcAKuAM}AMoAK{@?CMiAKu@SwAESW_BW{AUmASaAa@eBKc@a@aBy@wCs@{BSk@Qi@[{@k@wAo@_Bk@oAu@}Ac@y@O[EIwAiC}CyF}E}IYi@MU{B_EaEuH_@q@qBwDYg@GMa@u@eB}CwAiC}CyFoBqDsAcCqAaCUe@uAeCeCqEc@y@k@gAw@aBO_@O_@M[Uo@Qi@Oa@Og@YaA]mAIYK_@Mk@ESIa@UeAKi@Ie@Ku@m@yD}AuJSsAYiB]{BqAeIcAsGgBaL[mBIm@_@{Be@uC?AIk@AKIa@w@eFKm@[mBcAwGu@wEk@mDk@sDyAiJ?CYeBUuA_BaKyBkNq@iE{AsJKm@i@kDO{@Ko@wAcJkBsLyAwJKg@a@iCW}Ay@gFKm@?AEWCS?ACGGe@W{AIm@m@yDKm@c@mC}A_KqAaIG_@AOs@kEAKCOKm@eAyGs@uECOG]COEYkAuHsAuIQaAIm@G_@Km@YkBKm@COO}@c@wCgA_Hm@sDG]COIm@Kq@m@uDG_@COAISoA?AKm@_@eCWaBYcBu@aFg@mDa@}CQqAIw@S_BIo@Iq@a@sDE_@CWGg@UqBWaCgDg[s@}GIu@iAkKSiBq@eGiAsKg@aESsAOaAOw@SkAa@sBa@eBMk@Ok@Mi@Qm@a@}Ak@iBm@kBi@uAQe@g@mAa@_A[u@u@aBq@oAw@yAq@kAAAU_@KOOWIM[g@m@}@W_@k@u@_AkAuEoFuGyHk@q@Y_@IIc@m@s@cAm@}@a@m@_A{AMUq@kA}@eBQa@s@yAISs@cB[u@_AiC}@kCOg@a@yAGSGWqAkFe@aCQcAg@yCm@iEkCuRuDiXg@oDYoBc@kCg@eCu@iDkAkEg@cBw@_Cg@wA_AcCaAuBu@}A}@cBkBgDaBuCuDyGmA{Bm@iAaAsBcCyFg@wA{@iCq@yBmAuEk@iCe@gCa@sBIc@[aC_@kDOyAWsCSaDq@gOw@}Pq@wOEaAwAw\\KyBScFYuFc@qJC_ASmE_@cJC_@Eq@Ey@MiBI_AMkAK}@QaBc@eDg@}Ci@wCi@cCq@sCm@wBu@cCu@}BaAeCgAeC_@y@MYSe@Ug@Ue@eKaUwA{Ck@mA_AuBUe@Ug@Ue@wB{E_BkDaCkF{JiT{AiDo@qAcDgHg@eA_GsMcAyBsDcIyAeDKSSe@Ue@gA_C}D}ISg@Ui@y@sBe@oASi@Sg@e@qA}B}Gs@}Bc@}AcAoD{AeGKe@}BuJi@{BmLyf@yFqVsEsROm@mFeU{AuGyAaGm@{By@wC{@}C_AuCi@aB?CGQWs@Uq@[y@_@eAm@aBg@oAq@cB]u@e@gA]u@q@yAs@wAa@{@s@wAs@wAcAmB}AmCw@sAw@qAsCyEu@qAw@qAmBeDw@qAoBeDaG}JkAuBc@s@S[Q[e@u@c@w@c@w@}AgCgAmBACWc@]k@Q[S[c@u@e@w@c@u@c@u@c@u@e@w@S[c@w@w@qAc@u@e@w@c@u@c@u@e@w@u@qAQYYc@KSKQk@aAiAmB{AiCe@w@iAmBQYS]c@u@c@w@e@u@c@u@s@mACES]OYe@u@e@w@a@u@e@w@k@eAYi@e@y@a@y@s@uAq@wAcAyB_@y@O]o@yA]{@a@_AO_@[y@]}@]_A]_Ag@uA_@gAMa@M_@M_@M_@M_@Ma@K_@{@sCEQY_Ac@aB_@wA]sAa@cBq@eCI_@cBmGOk@Mk@kGcVi@yB_AqDe@iBYcAUaAK_@Mc@c@cBWcAc@cBc@aBYeAc@cBc@cBKa@Uy@wBqIMk@c@_BS{@[gAMe@U{@UaAOg@sAiFa@aBa@yAq@mCk@yBe@iBGSw@}Cu@uCu@sC}@mDcA}D}@gDa@}Ag@qBc@cBWeAIYOk@c@cBKc@o@_CI]gAiE}@kDWcAo@gCWeAc@aBUy@S{@Qs@i@qBi@sB]iAYiAa@eB?Ac@aBWcAs@mCOk@Me@s@sC[oASs@o@eCo@eCc@cBW_Aq@iCMe@Sw@i@uBS{@WaAWaAK[Ke@YeAa@cBWaAc@eBq@eCaAsD_@uAKa@Ma@Uy@Oe@W_AIW_@mAM_@Ma@M_@[_AM_@M_@[_AGQSi@Oc@[_Ai@{A}@kCqB{FkAiD}AoE}AqEyGsRQi@kAeDmAmDUq@Ma@[}@w@yBcAwCOe@e@qAs@uBYw@Qi@KYm@eB_AoCCIu@uBUq@Yy@Oa@Qk@GQIWEKK_@K]Ma@Ma@W_ASu@Ok@Kc@Kc@Ia@_@cBSgAIc@QeAOu@Im@ACUwAMu@m@mDOcAo@sDk@oDm@mD_AmFuBqMIi@Y_BKm@c@kCIa@AKk@cDSgAIm@O{@My@m@mDCMi@eDMs@SiAg@uCcAaGQkAOcAIg@c@oCmA}Gw@wE_@{BYcBEUKq@Kk@O}@[kBQeAQkAMw@g@wCm@oDc@oCG_@QaAKk@I]Ia@Ka@Kc@Ka@WaAKa@M_@YaAGOGQK[Oa@M]O]KYSc@m@uAYk@KSOYIQQ[GMU_@OWQWS[a@m@QYk@w@U[SWi@m@k@o@UWSS][e@c@YUUUWUWSUSWUSSYSUUUSUSWSUUWSUSWUUSUSo@i@k@i@WUAA]Ym@i@cA{@c@_@o@i@aA}@cAy@WUeA_AcA}@cA}@g@a@g@c@SQe@c@m@i@eA{@k@i@eA}@m@i@k@g@o@i@eA_Am@g@aA}@o@i@k@g@}AsAcA}@{FcFiC{BoD}CoCaCmC_CeEsDuBiBA?][{@u@cA}@eA_Am@i@o@i@GEgFqEa@]gAaAkC_CkDyCgA_AqCcC][iDyCgA_AcA}@_@[mBmBOQc@e@UUg@m@QSY]UYW_@UWOUQWSWS[U[QWe@u@c@s@Q[S]c@w@s@sAq@uAk@qAg@kA_@}@KWGQYw@KYM_@M_@M_@Qg@I[g@cBWcAYeAKa@Kc@UcAUgAUeASgA[iBQgAOkAOeAS{AWcCKgAOsBEe@Ck@CYGkAIwA?MCq@GmA?IKmCEeACi@AGI_CEw@C_AAKEkA?CIqBEk@W_Hm@oOCo@W}GCo@IsBKeCEgAGgAEiACe@Ae@C_@EkAEiAEeACe@Aa@GiAEiAEgACe@Ac@Ce@GkBEiAKwCCaAAe@CiACiAAcAC{BAq@CqGAoBEiIAkAAeB?SAkAAoDEsIAsCAyC?EEoLC_E?_@AaBAgC?ACaEGcHEeLEeHC{DA_C?YCeGAw@?y@AyAAaBAuDCeFCyDA}DC_FAkAAsBAqCAuBAqB?oBAqA?cA?cF?yD?aFAiH?wD?iT?aH?aC?oH?wK?uIAoC?o@?qC?_F?iA?oB?i@?cB?yF?sE?uC?kC?y@?m@?kA?mB?eBAo@?{D?oH@iDAkB?wCAgB?oF?yL@_F?iG?aC?O@kG?yD?oB?_C?}D?qD?eE?}DAeG?uC?{D?w@?eE?o@?oC?aEAw@?wAAwBEcFCkBCoCAo@AiACqBEqCCsBG_FEyDIaGMaKEmD?EEkCAsAKqHGcGGoECeBE{CIaH?c@Ao@C_ACuBAaBGsDG{FEqDEaEAQ?[Ac@?OCqAE{CG}DKgKAUKaJCcCCoACoBAaAGeFAiAAc@EqDAy@?WAs@?WC[AYAuA@_B@gA@{@FuA?OJ{A?CNkBJy@D[d@wDv@{FFm@nA_KDYlAmJJgALmBHwABaA@}BCsAEqACWAUGkAEk@?AAOK_AEc@Gg@Ec@COCQEc@Ea@MiAGe@OsA?GIm@YqC[sCa@wDa@mDa@sDAEQcBYiCMmAMeA]qCKaAWmBM_AMgAIk@OeAYqBe@yC?CKi@G_@YgBo@{DuDwUo@}DuAqIk@oDU}Aa@cC]kBg@aD_@mBEQuAcG[eA}AiFO_@Og@O_@_@}@]y@GKUi@k@iA[o@qAmCg@aAKW_@w@Yg@MY]q@cAqBEIUe@w@aBwCcGOYk@kAyAuCYq@_@_A_@eA_@cAQi@a@sA]iAq@mCyB_JaA}D_B{GcAgEa@_BeCkKy@gDqEcRkAwE{@uDeAmE{@gDYqAOi@c@aBoCeLu@cDa@eBs@oDQaAMu@QgAAAIo@QeAMaASwAg@sDQiA?AAGE]AC?AKq@cAsHe@_D?CM{@s@aF{@mGw@qFsBeOm@qEo@wEc@gCQcA_AoDe@{Ai@_Be@sAmByFiKyZs@uBi@yAUo@m@gBe@oA{@eBg@cAg@q@o@}@e@m@k@m@k@g@aAy@{AgAkDgC}@o@kDgCkA}@IIg@_@[YcA_Ao@m@o@o@a@c@i@q@U[o@w@g@s@s@eAs@gA{@yAo@mAm@oAg@mASe@m@}AUg@Qc@w@eCg@eB[sAUy@[sAqA{Gy@qEa@uBk@{C[_Be@gB[mA]aAQi@Sc@Wq@Ui@GOWg@_@s@e@}@m@kAoDgHeCaFi@cA?AkCgFKSy@aBw@{AaC}EYg@o@qAQa@Ym@a@aAe@oAUs@CK]gAUaAGYI]Ia@WmAIi@Ga@M_AGc@Ks@G{@G{@IyAC_@ASCu@CoAA}A?}A?UAq@?aB?mAA}EAmB?qCCqP?oAAw@?wB?qACgB?WAa@Cq@IqA?AEo@KcAK_ACIUsBIe@Kw@Io@e@uDCSGs@Iu@IoACg@Co@Ai@KgCGeBCs@OqFc@eQQeHGeCGcDCe@Ao@Cq@[cMASGoCO_GAa@A_@A}@EkAEeAA[IwAIeBM_BK}AQoBU_CKgAOaBMaBE_@UgCG}@UaCYqDOeBEk@GaAG_BEs@C}@Ay@CeBAeB?gB?}@Ac@AiDAmCKcSE_D@aEEcCCuDCy@IoBCq@MkBGm@SwBE_@S{AM}@UwAMs@GWIa@]{AUcAi@oBe@iBg@iBkAkEaAqDeCiJkAoEKa@u@kCg@iBq@iCW_AMk@Ka@Mm@Qy@QaAMq@Kq@?CM_AM_AGa@Ee@Gk@Iw@Es@Gw@GgAG}@Aa@Co@KsGC}KEcOGeYE{KCaKKsOC{LC_DCaHGwP?{@?eA?{@@yA@i@BaAFuADmAFu@H}@Dm@N{AHy@J{@NaARoAP_ARcAVmA^{Ab@cBl@{Bl@wBf@kBVaAXcAV}@T}@h@qBj@cCf@iCNw@Lw@Hu@Hm@Hy@NyALyAJyADw@Bi@@e@BkABkA@oA?gA?yACyCGiCAwASmKQwI[iQOoHCwB?E?WEkCYiNA[ImEAcAA_B?eB@y@@m@D}@HoBJsAZqDHq@NeAPiANy@Ns@?APw@|@iDX{@`@oA^}@h@qAd@_Aj@kA\\k@^m@\\o@d@{@`@w@d@y@^s@d@{@l@iAh@gA\\w@^}@\\_AFOHUDMDMJ]J_@VaANo@Pu@N{@VwANcAHi@Fg@Hy@JmADe@Bm@Bm@Dy@BeA@i@@c@?eA?c@?u@GuLAwCAgGA{EGiLE}GIsWEiIAoD?O?I?KA}EEiLEmFAeEC{FG{IA{DG_LCqCGwCGqDEgCG{BMuEEyAK_DE_AQoEGoAIeBUqEUqDKaBSiDi@oHe@cGm@sGw@mIqBcTGo@iAmL_A_K]iD[eDGo@mAwMY{COsBQiCKiBIeBOeDKkCAGIaDGeCCeBAs@EyDAeB?wA?qB?c@?cCBiDF{DDwD@kABaB?MDwDDqCB}CLmJJyJJ}GBaCNsL?q@TmQLqKRiQDsCVoT@o@HgHFsFN}LDwDBu@?}@?iAAmBGyBEaAImAK}AIiAMmAGm@OiAQkAMw@O{@Oy@e@{Bg@gCk@mCmB{I{@cEm@uCI]WoAIi@yA}Go@uCG]k@gCMm@sAoGwBaKuB_KMm@SaAcB}HsByJgEmSsD}PaAmE}@iEy@yDm@wCs@eDCKWmAm@uC_AkEqAiGiAoFy@wDo@aDq@eDy@iEQ}@Km@WyAm@yDAAKo@OcAO}@Ks@[yBWiBQmAE[Im@Gi@MeAOmAGo@Ge@]}COyAAEEi@Ky@OeBKgAAKO{AUuCIiAKyASiCEy@K{AIoA?OCa@Eo@E}@GqAUgEEaAIuAKeBMgCK{BUoEKsBG{@OsDIuB]iJKwCE_BE}AEgBEcB?WE_CEgCAu@C}AEwCAq@E{CI}FKgK?a@CiCM_J@iE@aB@o@BcA@_@BcADmADoADw@Dw@HaADu@Fu@HgALiAPaBLaAT{AHq@FYFa@@KHc@Fc@He@FWLs@Ha@Ns@VmAPu@Li@R{@Je@Nk@Pu@\\oAXiAVgAZqAh@yBh@sBFWLk@l@aCp@uCp@kCr@sCBINk@H]Ry@l@cCd@qBb@gBXmADQ\\uAp@mCl@eCnAgFn@iCH_@FSFYDUFUHc@Ls@Jm@ZmBLiAHo@Fq@De@Fo@Dg@Dg@Dm@DaAFyABu@BaA@{@?E?s@@u@?g@A_BE}FCmD?[?A?A?C?QAqAGeKAc@EqJCoJEiIC_D?c@A_B@cB?S?sABiBB_A@aAHcCHcCDaAJ{BDe@Bo@Fo@Dm@F{@Do@Fi@Dc@Dk@Hy@V_CHo@Ho@DYHk@Hk@Jw@Hg@PeA?ANcAJi@Nw@BSJi@Ha@Py@R}@Nw@Pq@Nq@\\uAPo@T{@Po@J_@J[b@yANe@^iAVy@Na@HSTo@\\aAXq@BGXs@Vo@Ti@N_@\\s@f@gATe@Vi@h@iAZm@b@w@j@eA\\i@LUPWv@sArDgGfAiBv@qAx@sAvAaC\\k@lAqB`@o@\\o@Vc@BGx@_Bh@kA`@{@^aAr@gBTm@b@oA`@mA\\iANg@V}@VcAb@eBXmALk@P}@@AJo@Nw@Jk@P{@D_@He@Ho@L}@Jw@Hm@JcALgAPqBDi@?AHaADk@FcA?MBa@@M@_@DcAD}@@m@Bk@@cABcB@_B@_D@mB?gA?iA@S@sG@aB?aB?[BgD?]?Q?A?k@DeGDcDBoBBaCDsBB{ADkADqADoAHaBVuGTsE@OBq@r@}NpA_XPuDDoABg@JeBToEJkBNuDPaEDsABq@HsCHyCBwADeDBsADgC?m@@{@@oC@yEAsD?o@CiCEkEIwKEqDA{BCwCCyBAoA@gC@s@@o@?YDqBDoAFuAFuAFaABWHuATiCVkCl@eFZsCfBePRyBd@uELcAv@iHRkBj@aFXwCFs@F_AJmBDw@Bs@Bu@@e@@e@@eA?w@?c@?kACuBAs@Ca@GeBMsCYqEKuBq@}KAWEq@[qFa@kH}Bca@e@iIEq@}B{a@g@uIY{EEs@Cq@I_BCq@EsA?ME}AEsCAuBAoA?g@@oEFaFJyDNwDNyDF}A\\_Jj@qPLcDlCst@@CDiAt@iT@W@YPiEFyABs@HsAHy@LmAN{ALw@VaBXwATiAl@qCZmA@AZiAHYHYTq@Nc@FOl@}An@aBFMHMr@yAh@aAl@aAh@{@T]RWj@w@h@o@t@y@d@e@DEh@k@lDmDnCoC\\]\\[jDmD`BgB^c@RWT]Zc@RYBCP[`@q@d@w@z@{A~@mBj@mA`@}@`@eA`@kAL[Z_AVy@d@cBXeAXgAR}@XuAP_A`@{BBUNcAVoBLoAN}AH_AHqAH{AHcBD_A@g@?_@BkA?u@@mB?aA?i@GqECaBGsDGcDCaB_@kXAq@AU?A?CCkAIiFGoEAe@OuJSiOMwIAoAIuEAq@IsFKeH?Ao@yc@Ak@?CCo@GwGEkA?ICaAIcH?]EkCAu@?AAo@?ACy@Cy@MyCQiD[sFWyEAUEq@_@cHEo@u@_Ne@yICq@UwDi@oKE}@mB_^MqCa@_HEs@Cq@o@iL_AgQ}@}PwAgWWcFO}DIuBE{AI}C?e@EkBC_CAmCAmERiU`@iZBgCFeGFsDNwK?EJaId@ib@R{OVmSFoDDqCFiBDqAFuAFcBTsDNmBH}@Fq@TcC^qDVwBh@uDTkAd@iCb@aCj@cCd@uBtAqFtD}Nl@eCNk@tAuFh@wBj@iCTmAd@mCViBViBZgC@CPoBNkBNuBL_CHoBBw@Bq@?GB}ABmC@q@?o@A}BAyAA_AA]CqBO}FO_HCaBCm@IgEEaB[aO_@mQu@k^IoFAaD?oA@yA@}ADmA?QZwH~@wLDo@XmDr@cJFo@jDcc@Fo@VcDfB_Ur@aJRgC~@kLx@iKNoBLwALyAP}APeBvBcSZqCxB}RnAkLHo@lAuKhAqKHo@rBkR~AwNrAaMFk@fA{Jd@iEXwBVaCTsBT_CPiBLcBFaA@YFmAHyA?KH{BDmB@gA@{A?iEA{BCuJCkJAaD?sFCoJ?}AGwYEgPAuF?q@C}JE}WEwM?cASmb@IkQAo@?GMo]Om[KsVE}IAo@CuFCeEAqCEgHEkMAgCGmMAeDAeB@cB@wBDcCHcCJ{BH{ALoBNmBLiARkBTmBViBHg@NaAZiBLo@R}@\\eB\\uA\\uAd@aBf@cBX_AX{@L_@`AgCHUbAoCXs@r@kBb@kA\\aA|@_Cd@oA~F}Or@iBzEoM`AgCl@_BVu@Vq@dBuEp@iBNc@Ts@l@iBt@gCf@qBRw@R}@TgA\\aBPaAZkB`@qCXyB@KZ}CV{CB_@Fw@Be@Bc@DaADiADqAFyBBuB@gB?{BAiAC_CKoECk@GeCOcGO}FCs@CqAE}ACcAIsCMyEe@aSUsIM{ESeIWwJYgMc@uOUaKACGeDEmAAq@CgAI{EG_ECkDCmDAu@?gBAyB?sF?gE?wE@yJCmJEkGA_AAoACgBCoAG}DGeDO}FEkA]mKUeHUgHM}DOuEWkHEkAOuEMoEA]e@aOQkFUyHW{HCg@OgFCi@?OC{@?ACo@GgBEeDAmA?sB@yBBsBDyBL{CJwBHoANmBJsARoB?A\\oCZ}BZqBLs@r@iDVqA\\uALk@f@gBZcAx@mCVs@Pi@Vq@Z{@Nc@Zy@fAyCz@_Cj@_Bj@{Al@}Ax@_Cj@{AL_@Vq@\\cABGhA}Cx@{Bj@_B`@gAVu@f@_BXeAb@aBb@eBh@aC^kBZgBZiBViBNkALaARmBPiBHgAJuAF_AFwADq@@[Bm@By@@c@BuA@m@@]?i@@y@?{@?}@?q@AaCAS?o@?AAeAAkCAeAAoAAaBA_B?qAAaACaD?_@M_Sg@o|@EaJS}ZAuASa^C}DEsFAwCAkA?iA?gA?}@?q@@gA?g@?e@@g@?a@@c@?c@@g@@s@@]?A@o@@]@U?U@W@a@Bw@H_C@c@Bg@L{CJ}BP}CFaAB]TeFPeDb@oIjBy^?CD{@Ds@@]@_@Bo@Bo@@eA@_@@[?i@@_@?a@@g@?c@?q@?[?YEyEEaCIeBCs@O{CUqCGw@Iw@Eg@QwAE[Iq@Gg@Ge@Ge@QiAKk@Ig@Ga@GWCOG[Ia@Ms@gAwFs@kDe@gCq@iDQy@Ki@AIMk@_A_Fg@iCAGG[G]Ic@Ga@Gg@Ku@Kq@M_AE[Gi@KcAIo@Ec@C_@Ea@Ea@C[Es@Es@Gw@Cg@Ce@?ECk@?CE{@Ai@Cs@?WCaBEsBAaBA{AAwDAqCCoB?iAAkBMcUMqUIoPEcIEcF?gAAgBAgA?eA?s@?m@@mA?a@BoB@y@BgA@e@Bc@@c@DiADiABq@FsADq@Do@LcBHiADc@@SFk@JkAN}ANsAVyBl@kFf@iEpCkVd@_EJaADY@KD]?EBWFs@B]Fs@Do@@c@Bg@Bc@@a@Ba@?[@W@]@i@?a@@a@?i@?a@?S?UAi@?]Ao@Cs@Am@A_@Ce@EaACe@C[A[CUEc@Cc@Ee@Gg@E_@Io@Io@Ik@Gg@Ii@G]Ia@G]UgAIa@S}@GUQs@Og@Oi@Ka@Sm@IWOe@Si@[y@EMGOM[Q_@Q_@O_@Q]OYa@y@m@gAo@mA_AeB_AeBkC_FUe@mC_FkK{RWe@g@}@kA{BWe@We@g@aAs@sA{AqCqD_HuKiSs@uAOYg@aAAA}@cBy@mBk@qA[u@eAsCs@}Bm@qBa@}Aq@mCS}@SaAKi@CI]qBWuAa@uCg@iEMoAMyAOoBQqCEu@OqEGkF?_B@}CByBF{BHeBJeCHkAPcCH_Af@}ENsABOFc@RoAJo@Ly@Ny@d@eCd@kCxBwLl@iDnCgO`@}BjAsG^sBd@gCvA}HZgBZgBRgAReAZgBRgAlCaOn@kDRkAd@mCTgARiAXaBP_A@IN_ApDuR@EZkBjBeK\\mBp@sD\\kBbAyFV{ABMBO@EJo@nA_HVwA~@gFBK?ALo@bA{FVsAF[fDyQPiAf@sC^oBN}@h@uCp@uDDQt@cEvBqLr@{DJm@h@uC`@yBLq@lA{Gb@aCJm@Lm@DSx@qEHe@Lu@|@_FlAuG?CRcAPcAJo@DUFWHm@Fc@Fc@Fc@Dc@Da@Dg@HeABg@@G@e@B]Bw@@i@@s@@m@?aAAs@?I?QA_@Ae@?I?SCk@OsDK_CKaCO}CMaDImBQwDMuCKmCMcCKqBA_@E_ACo@AEMqCGoBEkAAe@C_@Ag@EoAAu@Aq@?{@?y@?_@?S?]?k@@aB?I?q@"
                     },
                     "start_location" : {
                        "lat" : 42.7716955,
                        "lng" : -84.66901059999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 mi",
                        "value" : 1856
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 76
                     },
                     "end_location" : {
                        "lat" : 42.9771945,
                        "lng" : -82.4762774
                     },
                     "html_instructions" : "Take exit \u003cb\u003e199\u003c/b\u003e on the \u003cb\u003eleft\u003c/b\u003e for \u003cb\u003eI-94 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eI-69 E\u003c/b\u003e toward \u003cb\u003eCanada\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "kbheGpuovN?mF?eAAcC?s@?u@?sC?O?e@?aBA}@@gG?}BAq@?c@?MAqEC}AAy@AWCaACs@GaBEq@Eq@Eq@Ck@[iECWK{@Gk@Gi@Ky@Kq@Km@KWEQIo@AGS{@UeBEMk@kCa@wBo@sC?C}@yCYu@Uk@s@}A_@o@EGWc@EGSYQY]a@GGuA}A}@w@_@Y[QMGQE"
                     },
                     "start_location" : {
                        "lat" : 42.9727029,
                        "lng" : -82.49704679999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 mi",
                        "value" : 2189
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 75
                     },
                     "end_location" : {
                        "lat" : 42.99025140000001,
                        "lng" : -82.4610634
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eI-94 E\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "m~heGvskvNKIMIMGIEIEGCGEICIEECCCCACAEACCICGCIEICMEKEQGWIUIUEOEKAGAICIAG?GAo@Is@Gi@EOA{AMe@EyAMq@GaAG}BQaAI_@CgBMi@Ig@Ie@GYGYGk@Oi@Og@Oc@Q]Mi@SOGYOa@Uq@a@k@_@SOOMs@i@o@k@q@s@i@k@c@i@[c@Y]c@q@k@_Ag@}@IQm@mAYo@Oc@a@cA]cA[aAUy@I]Os@UoAKc@SgAKq@Ks@E_@Iu@E[AYCUAIIcAGu@IkAEy@Eo@KiDKgDAY?YAUAU?UCi@?a@GaCA{@"
                     },
                     "start_location" : {
                        "lat" : 42.9771945,
                        "lng" : -82.4762774
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 mi",
                        "value" : 2183
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 107
                     },
                     "end_location" : {
                        "lat" : 42.99796180000001,
                        "lng" : -82.43721979999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eI-94 E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eToll road\u003c/div\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "apkeGrthvNQ}FIwCSeKGgCEcAMoBU{CSgBYqBM_ASiAWuAO{@Os@I_@Mg@?CQm@YcAW{@]_AYs@gAmCs@iBa@cAQa@kAyCcD{I}@{B}BeGUm@CIISIS[s@IUIOIQISa@u@KOGMk@{@u@cAa@e@KKi@o@U[EGCCIOMUMWQm@AEIUGWEQGYEYG_@Ec@Ei@Ee@[gFS}C"
                     },
                     "start_location" : {
                        "lat" : 42.99025140000001,
                        "lng" : -82.4610634
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 mi",
                        "value" : 1130
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 148
                     },
                     "end_location" : {
                        "lat" : 42.9985223,
                        "lng" : -82.4237234
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eBluewater Bridge E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eToll road\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Canada (Ontario)\u003c/div\u003e",
                     "polyline" : {
                        "points" : "g`meGr_dvNO}BC_@ASGeAUoDI}@I}@AI[eBACOcAGSCMIc@o@mDAEGa@Iu@Gm@AMAIGs@Gw@SkDEq@C_@Cm@Ac@A]AcA?y@@a@?[@YB_@Bg@BY@O@OBQDg@Jw@BWDYHw@Fg@RiBBSFg@^yCDc@R_BD]"
                     },
                     "start_location" : {
                        "lat" : 42.99796180000001,
                        "lng" : -82.43721979999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 mi",
                        "value" : 970
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 90
                     },
                     "end_location" : {
                        "lat" : 42.9946397,
                        "lng" : -82.4132848
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eBluewater Bridge E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-402 E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eToll road\u003c/div\u003e",
                     "polyline" : {
                        "points" : "wcmeGfkavNHq@P_B@In@kFBQ?AReBlAeKFg@Jo@Js@H]Ha@Nc@BKRi@Vk@r@yAr@yAtAaDh@gAlByDbAyBdA{B"
                     },
                     "start_location" : {
                        "lat" : 42.9985223,
                        "lng" : -82.4237234
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "63.9 mi",
                        "value" : 102855
                     },
                     "duration" : {
                        "text" : "59 mins",
                        "value" : 3557
                     },
                     "end_location" : {
                        "lat" : 42.9105287,
                        "lng" : -81.2264859
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eON-402 E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eToll road\u003c/div\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "okleG~i_vN`BeCp@cAz@u@\\[bByAb@a@\\Y\\[z@w@\\YFIl@m@jDqD~@cAPUTYT[RYb@q@R[DIBGDIL[BEBGl@gADIP_@HQJYPa@HWb@oAV{@Tw@R_ABOZwAXkBPwAJaAHaAFmABq@@QBk@BuA?_@DoCD_CDyB@cB@qA?GFaED_DDuD@IFmD@sBLkIDsDJaIFkGBeA@eA@uABmBBuAB}B@{@@UB_B@eA@o@@yAByA@iABgBByA@{@@]@wA@y@DuCB}BBuBBwABwABaB@wAByABaBBkB@}@B{Aj@ad@PuND{CByA@yABcA?s@?y@@oAAk@?AAk@CcACw@E}@KuAKeAI}@Iq@Ga@Gk@kBsLO_AOaASuAc@kCKu@gAcHwAgJwAcJi@qDa@kCAGYeBc@qCUeBEWIw@MaAEe@IeAEaAGuAEoAAsB?C?u@AcB?{@?Y?c@?Y?IAoA?a@?EEyWEkSAaHAaD?aCAqDAiF?yC@gD@mAB{D@w@FaIFiEFyHBaCFeFDoDBiDDgELwMBaDD_E@}@FgERmT@c@?o@TyULqLBuB@cEA_AA}@Ay@A]GsAKwAA[I{@Iw@Kw@QqAMy@WoAOu@I[Qs@g@eBUs@IWIYMYWo@Wo@Sc@CIMWCEWg@s@yA{@cByAwCUe@O]MWKWWq@Wo@KYIWUs@IY[kAQu@G]IYG[GYG[G[Mu@My@Iu@Iw@I{@CYC[C]C_@Ew@A]C{@Aw@Ay@A{@@y@?y@BsB\\ob@\\uc@JwKDaHDiFDkD@qD?KB_EBkEFuLDgH?q@@_@D_IDoI@cCDaHF{K?k@f@ebA@oCBgF@i@@cABgFBoGDaI?q@FsLFsLBcA@yCJ}RH}RLwR?YFeLDiGHwPf@k~@?_ADmGV}f@DsFDaI@qC?WHuKBmE?q@?YFwHDmKFuI@aFHmLLySB_IB{FFaKD{G?e@LsRBkFBoEDkG@gA?mBDiFBkCD_I?_CB}E@_DBcB@mEDuK?o@JaZLg\\Puh@@_HBwF@o@@eBDkQBwE@gD@kD@uC?oA?YDcIByKL{d@@o@JuZFoNBcD?WBwCDmBLaH@c@FyCBk@DqBXkIZeKBk@FwBJmDF}CFsCL{HDyE@oBBgGAqO?[IyRImRAoCCwHAaCAo@AyDKqTOy`@AkBEmLIyQKoWAYCqHEoIIsREiL?aBCgJCiNAmQ?g@?GAe_@?Q?E?]?wDAwC?yB?yA?}@A{A?wC?{A?yAAwC?sB?yDAuB?{D?wCAyB?{@?yBAwB?oD?_B?}@?UAwF?wD?yBAwC?uC?{A?oDA{C?oDAaC?qFAsE?uA?_B?}@?uDAuD?sEA{A?]AmI?I?U?m@?cD?wDAuC?{A?yC?[?M?mBAyB?{@?eB?wAAkD@yAAyB?yB?sDA_@@QAiA?wB?qG?u@AM?qB?wB?{AAuA?{B?wEAuC?qGAkG?M?iGAqD?wD?wB?yBAsD?uCAqF?oE?oDAuC?uA?wB?wAAsC?wA?qCAsD?{@?U?sDAuB?uB?sB?aA?oD?uC?y@?uB?kB?y@@y@BsA@a@DsAH{BD{@HqAFaAFy@JoAH_ANuALmAPwAPuAR{ANoAXyBNmARwANsAJ_AJqAH_ANuBJuAFsAD_AB{@DyABwAB{@@qA?{@?yAAyB?m@CkAC}AAOIaCMsCOsCIwAMsBG{@QsCIuAMuBYkFKiBo@kKk@}Ja@eHSoDG{@QoDMuBMuBQsCEu@QwCE{@GuAG{AIuCAy@CsB?yAAy@?_B?w@?[?E@iAAcD?qDAgI?{B?yA?mFAwA?_@?uB?_@?uB?sC?sC?wBAkG?iH?kE?aB?uCAmO?qC?yBAiF?sB?}B?yA?wAAaJ?mF?sC?mF?uBAqE@oA?q@AiD?sB?uC?w@AmC?aK?}L?uB?Y?wCC{]?aF?uC?{@?mFAsM?uH?mB?gCAc@?}N@aEAiD?q@?O?cC?aD?{AAuA?cO?kD?qB?gA?oCAiF?o@?sC?cEAe\\?aBAqn@Aam@A{c@AsW?aEAaS?q@?w@A}[?q@?eNAuc@?y@?{D?q@AeH?q@?_S?o@?eE?eH?uF?G?mF?q@AsZ?qQ?uEAwJ?q@?{B?{E?qK?yAAuF@iW?_LA_V?e@AoLAoNAaRAmOAkEAoOAgS?C?_S?o@AuJ?oN?aD?mFA}E?kT?cU?aF?y@?oUA__@Aib@?q@Cy`@?o@?sC?aFA_O?_E?kMA}NA{\\AyO?_EAuQ?qI?wA?mR?eC?uHAyJ?[?{@?mD?mD?uC?aI?i@?q@?uA?mD?qD?iF?oC@yAAoE?kE?kE?sC@kE?{AAu@@{@?wM?oC?y@?w@?yB?[?eH?kF@gF?oQ?iP?{J@qE?qY@eJ?kE?cG?q@?qIA_F?_C?eBA{PAaT@sL?_@AkA?aC?mJ?oCAuH?oD?c@@aA@eAAoG?mCAuD?iDAwBAo@@uCAiM?oC?kD?kA?g@?y@?{@?uA?w@?{@?mCAiF?oC?sC?uB?mC?Y?q@?}BAsC?iE?oE?C?cE?uA?_@Ay@@]AqB?c\\?[AwK?{KA}Q?C?cE?uA@iBBiBBk@@a@FiAFcAHkAFq@Fs@LgA?GR_BPkARmA\\gB^cBXeAf@mBb@sAb@mATm@Xu@r@}Af@gAh@aAXg@fBqCbAuA`B{BBGfDsEJMdCiDfAyA^g@\\c@DKBEZc@z@iAxMuQ|CiERYvIqL?AnH_KpEiGxDiFJOxEsG~IyLz@mAhE_GzCeErBqCbF}GfCkDnAgBfAcB^o@z@}ATe@d@aAb@cAN[b@iA^iA^gARq@`@yANo@ViA@CVoA^oB\\{BHo@L_AHu@Fy@PqBHsAJ{BVwFJcCHwAHgAJwAPeBLeARuAZoBXuA@ELk@R{@d@iBb@_Bb@sA`@iAn@}A@CPc@f@gAXk@LWn@iAd@u@`@q@l@_ABC~AcCdBkClCaEJMnCcE`D}EdDaFXc@`BaCpAoBbA}A~A_CnCeEnAiBVa@`@m@~@uAh@y@f@s@n@y@^e@t@{@|@aAXYVWZWd@c@n@g@LI`BoArB}A~@s@~@s@xBaBbAu@r@i@|BgBp@g@dAu@rAeAf@a@TQJIdA_AfAiAp@w@Xa@DG^e@h@{@j@aA@Ch@cAXo@Rg@\\u@Tq@Vs@\\gA`@yAPw@\\yARoAPgAPmALiAJkAF{@FmA@OBu@DwA@y@?}@@_C@kG?cMBuP?_D?q@?gC@sH?uC@oG?iE?kC@cA@sABuA@{@Bq@H{ALuBFs@LwAVyBPoAZkBt@qD\\uAHWJc@Rs@^kA^gA^_ADKRg@`@_A@CRa@f@cA\\q@HOl@aAx@qAz@sA@?b@o@rB_DLQ~@wAFIdA}At@iAV_@@Af@w@jBqC~@wAp@cANS@Ct@iA~AaC@AXc@dBeC?APWxBeDx@iA|BqDDIVa@bAeB\\m@NY\\m@~A{CdAqB`AuBf@eATg@N]lAkCx@gBlC_GVg@vG}NjBcEj@oAzGqNfAqBpA{BtA{B^k@V_@^i@p@}@h@u@^e@l@s@rA_BzA_Bj@k@j@k@h@i@TUTSb@a@bA}@dDeCh@_@b@[fAs@~AcA`Ak@\\S@A`DmBpEmChBkAvA_Ax@m@|@s@r@m@z@w@d@e@j@i@~@_An@s@fCqCrAyAfCqCDG`CiCbAiAPQtB_C`@c@fBmBnH_I~@cATWZ]pA}AjA_BhAeBt@qABGZk@h@cA\\s@Xk@`AuBTk@Vm@`@gA`@iARo@Tq@ZaA|@mC~@wClAyD~E}NlD_LL]h@{AnA_EdDaK@CL_@J]J[J[bD}JdCwHjAqDfAgDd@yAPi@Pg@DMtBsG|@qC@GfCyH@CbBgFRo@Rs@Tq@\\mAHWXgAR{@b@iBZyAVuAPcAJm@T{Ab@iDJcAFs@ZmDBg@@WBa@HuA@Y?AFsBDqBB}@@qB?y@?uAEqC?]Cy@Aa@MgDCg@AOGy@KuAGw@QqBOsAKw@]iCGe@QgAYkBE[yBoN}A_KsA}IAGIe@COKw@Mu@Mw@u@{EYkBKo@a@qCg@cDg@cD[mBg@cDYoBg@cDg@cDg@eDG[E[EYMw@Kw@Io@Ky@OwAQqBC[CYEa@Ey@C]Cy@C]A[Cw@?]A]A]A[?]?AAY?]A[?]?w@?_@?]@[?[?_@@[@]@y@@[@]@M?O@[B[@]Dy@B[@]B[B[B]B[Hy@BWHu@B[PsAJy@DYD_@Ls@D[FYF[F[DYF[Nu@Pu@Ps@Pw@Pq@Rs@Rs@\\iAn@uBBIfAqDfAqDHS|BwHbEaNdCiIp@yBTw@rAkERq@Ts@\\kARs@Tq@Rs@^kARq@X}@BM^mA^kARq@Rq@Ng@b@wAPm@|@_D\\oAPq@\\mAZmALa@VcAn@cCPs@l@cCPs@Pu@Ns@ZoAXmAF[Ps@H_@VkANs@Pu@Nu@Ps@TeABK^iBl@mCLk@j@gCDQP{@b@oBXqAx@yDz@yDx@uDNs@H[Nu@@ELm@Pu@Pu@VoAXoAXoAVoAXoANu@F[Lu@DYF]DYF]L_AHw@BMJ}@H}@Fo@HwAJeBFwABcABeB?gA@eAAk@?q@EeCAGKoCMqBMoBGw@AGw@{KGaA_@gFGs@u@oKEo@Gq@K_BuBeZEe@qAeRIkASmCOyBa@}EYsDUmCMsASoBIu@[yC]eDsAcLe@mD{@gGgHee@eBaLsB}Ma@mCgCqPw@gFi@sDKs@CQ[}Bi@{DYyBOmAu@sGYcCYaCUkBMmAMgAKu@MoAKu@?EOgAKy@My@OcASeAOs@Qs@Qs@Su@Wu@Us@[{@Sg@Wm@a@}@[k@c@w@_@o@a@q@GIiEwGuCoE{BgDMQiAgBsBaDmAkBMOwA{By@uA[k@a@u@]s@]s@g@mA]y@Yw@[}@IUY_AK_@Su@]sAMg@Os@Ia@Ic@Mo@Mu@Ko@Kw@Io@Gk@Is@Gk@I}@Gu@Ew@Es@Ew@G{AUiFc@iLYiH]qIm@eP[aIEiAEwAEsACw@A]Ay@AO?KAsAA{@?sA?mAAg@BkC?y@BsAB{@BsADuADqAJkCRcELcDD_ADu@ReEPiEJqBFiARuEDy@@]@]@W@_@@]?]?[?Y?_@A[?W?EA[AMAOA]A[E]C[Gw@EYC[G]Ku@G]G[Os@GYSs@Uu@Wq@KWKWISMYMWKUMWMSOUMS]i@OSMQQSQS_@a@c@_@a@a@c@_@SSs@m@[Yg@e@[Wi@e@cA}@{@y@y@u@_@a@s@s@{AaByAcBy@aAw@_ACCCAECCAMC"
                     },
                     "start_location" : {
                        "lat" : 42.9946397,
                        "lng" : -82.4132848
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "31.1 mi",
                        "value" : 49999
                     },
                     "duration" : {
                        "text" : "28 mins",
                        "value" : 1651
                     },
                     "end_location" : {
                        "lat" : 43.1183195,
                        "lng" : -80.7072723
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eON-401 E\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "y}{dGppwnN}JgMc@k@c@i@wD{Ew@cAsAaBiB}B_AkAiB}BqBeCkBaC_@c@iAwAaD{DaBuBgAsAg@o@[_@cC{CiJmLuAeBuP}SqBgCkCeDkGeIkAaBIIu@mA]m@y@yA[k@aAsBy@kBgAiCo@cBu@yB[}@[gA[gAOg@a@uAKc@GYq@_DESiAyF}@mEk@sCq@kDa@oBUaAG]g@gCc@yBQw@Ow@]aB[}A_@sBUuA]}BOcAQsAYyBOgASwAy@sGMeAg@oDE[mAoJ}@}GS{Ag@{D[gCOeA_@gDy@sG_CwQqAgKy@kIYcD]qEMaBGcAOiBGqAMoCGoAGoAIsAEu@KyBUaFIcBCe@_AwQ[eHs@mN]aH}@cR_@}H]}GEy@OgD[oGU{Em@_Mu@qOWoFe@yJIyAUkEKuBKkBE_A}Bue@QwDaAqSSsDUsEo@cN_@iHAQIsAG_AIgAI}@IaAYgCIu@OgAKu@YoBUuAc@_C]}AIe@U_AYgA[iAU{@e@}Ak@iBe@sAc@oA}AuEYy@Qi@cA{Cg@yAsA{D}FaQsCqIuBeGa@oAeAyCkAoDs@uBGQWs@w@cCWw@]iAOi@[iAWeA[sAWiAQ_A]gBUsAg@gDWoBSoBiGur@_@_EGo@kB_TAMOiBEe@C]U}BScCY_DeAoLAOk@uG]{DOcBg@wFe@uFi@{Fg@{Fg@{FIaAcDw^_@kEKkA]wDIaAo@sHQgBg@_Gc@yEQmB_Eid@aBeRAOGo@Go@Ca@k@}GwA_P{AyPa@{EY_D]sDuA_Pq@wHi@mGaE{d@m@cHeA{LcAaLSaCe@oFQmBe@iF{@aK_@eEYcDGo@aA}Kg@yFMqAmAoNaAaLy@aJe@qFKkAk@sGi@_G_@mEYcDGo@cAoLOeBs@cIk@qGYiDQgBMuAM}AGq@_@kEWuCk@sGi@cGm@_H_@eEUmCM{ACU]iEOuAQsBG_Am@mHGo@o@gIUiDQ{Bi@aH{Dud@g@oG[uDSgCo@}HYkDAOGy@?AIeAq@eIcAoLe@wFW_DGq@[_EyCq^Eo@UqCGo@UoCGo@i@_H_@oEMwA]kES}BEq@KmAg@cG]}DEg@?Gk@sGAMGm@KaAY{BIo@?Ac@qCWsAKm@G[w@uDo@eC[mAUy@i@eBACo@oBi@{Ai@uAWm@_A{Bg@aAk@eAs@oA[i@CEk@_Ao@cAs@eAcAyAMOuAkB{@iAW]AA_AqAi@s@Y]ACY_@oAcBcByBmAcBeAyAOSqBmCgAyAyAoBaAqAqBmC}AuB_BwB}ByCSYEGiAyAaByB}AuBAAo@y@o@{@mAaB_BuBk@s@k@w@cAsAYa@mBiCy@eAeAwAuAiBgBaCu@aAq@_AAAeAuAkBcCkA_BsD{EwC{DYa@u@cAoBkCmAaBoAiBo@aAi@y@w@oA_A{AyAiCaEqHS]yFmKuJsQ_FoJkIgO}CyFsBsDmBmDoFiKo@gAaGuKyMqVWe@m@iAmBoDkEcIsAeCU_@S]oA}BuB_EIOKSi@_AeFeJiBkDUc@aAkB[m@kA}BGKmBaDk@}@CG_AuAwBeDsCgEWa@o@cA{AaCIKYa@iAgBYa@}@uAi@{@c@w@cCwDcBkCiDkFyD{FsBaDeLgQm@aAWa@mFiI{FaJ_EgGcDcFMQw@oAkOwUcCuD[g@kBuC_AwAiPeWAA}C_FcA_BkAeBmKiPw@kA}AcCe@u@oBwCyBiD_BeCy@iAcEoGwCqEe@u@mEyGoByCy@oAcEmGkBuCsAsBQYeDgFaCsD}A_Cy@qAmBsCWa@kAcB{AcCa@q@iAgBMSKOMSkAgBcBiCkBqCsAsB{BmD{JkO_CoDyCuEqB{CmBoCc@o@]i@}@wAq@cAy@mACCoCiEuCkEmEuGkEsG}CwEwNiTuFoIsKgPqCgEuCkEsHaLoDoF}CuESYiRiYkAgBeBkCkEuGcFwH_G{IsG}JuFqJiGoK}@yACGGKIOKSMSyEgIcFuIwCcF_Q_Zi@aAaDwFUe@_AiBg@aA_@u@q@{A]s@]u@u@iBeCeGwDuKOa@c@qAe@sAaEiLs@mBsB}FkBkF{@eCgA_DsCgI}AqEM]k@_B{@cCgAaD_@gAISQi@i@}Aa@sAWw@Mg@Qo@YeAEKIa@]wAEQMi@YuAWuAIa@Oy@OcAIg@EYKw@Ge@Ky@AKGc@MeAKiAGq@UoCO{AyAkQGq@MsAe@_GGo@Go@Go@UgCOkBoA{Nm@cH"
                     },
                     "start_location" : {
                        "lat" : 42.9105287,
                        "lng" : -81.2264859
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "39.9 mi",
                        "value" : 64235
                     },
                     "duration" : {
                        "text" : "35 mins",
                        "value" : 2084
                     },
                     "end_location" : {
                        "lat" : 43.2275789,
                        "lng" : -79.954894
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork to continue on \u003cb\u003eON-403 E\u003c/b\u003e, follow signs for \u003cb\u003eBrantford\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eHamilton\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eNiagara Falls\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "opdfGlcrkNBc@B[MsBE_A?MKaBI}AEy@Ck@Em@OqBSuBIw@]kCMy@Mu@i@iCc@mB[mAc@iBIYe@gBe@mBYmAUkAM{@G[OqAGy@C]E]Ey@Co@Cs@AQAwA?gBBeBDuC@]@[@{ABkAJqGBwBBuA?m@?m@?wBA}@EoBE{@KuBI}AEi@Q}BQqBOsBQsBOuBOqBQsBM_BAOi@_HKsAEo@Go@Gu@c@cGyA}Q}A}Rg@uGk@gHuBoXm@yHgAiNu@{J_@cF_@iFYeEKuAq@eJ]cFs@wJWqD_@aFEk@K_BG{@SqCI_Ao@aJMeBC]ASOuB[aEWwDQcCs@sJ}By[SuCg@cHmBaXqCi`@?CEk@}AsToAeQCa@Go@UkDwAyRe@wGC[Iy@W_D_@wEGo@m@aHaByR_BkRGu@q@kIk@sG{AwQ{@{JqAqOgBaTEo@]yD}@sKi@mG_A}K_BmRu@cJ_@aFIcBMkCC_ACw@CeAA_@AkAAu@?I?q@Ak@@g@@oC?a@@u@B{@FsB@i@FmBDg@D}@Be@Dc@Dm@FcAHaARkBHw@pAsLP_BhB{PbBsO@IFi@Fo@nAeLbAkJf@sEh@cF\\}CBWt@aHTmBb@eEXmCb@_EP}A^kDf@kEh@aFXmCVmCVoCJwAD{@JyAHqBD}@@[@S@c@@}@DsBBuB?{AAcA?q@Aw@Ay@CyAGuBEwAGwAQoCUsCSqCUmCQwB]eEUqCg@cG[yD[}D[_Eq@}HMgBg@aGCWCYk@cHo@}H[sDKmAEq@CYWyCS{Bc@sF]cEScCMaBGo@Gy@YmDeAmMw@uJYiDI_Ac@qFGo@KqAi@}Gy@cKm@qHGq@c@iFgBqTi@yGsAgPgAkN}@uKq@oIEc@AK_@uEAEqCq]uA_Qg@aG[}DUoCSaCs@wIUyCGo@qAaPSaCmAaO_AwLAIm@{HKqAS{BQkBKcAOkBWqCYmCUoB]kCc@kDQoAUuA?AG]COOcAMu@Oy@UoAOw@}@yEe@wBYoAm@eC]wAGSGYOi@Ok@Ok@CEMe@Ok@Ok@Oi@EOK[Ok@ACOg@Ok@CIM_@Ok@Qi@a@wAQi@Ok@Qi@Qk@Ma@Ok@Qi@Ka@AAMg@A?Ok@Oi@AA?AOg@Oi@AAOi@?AOg@AA_@sAAA?AOg@?COg@AAMg@ACIWEOACMe@AEOe@ACGUGUOi@Qk@Qi@AEMe@A?Ok@IUGUK]CKYaA[oAe@iBYmA[mA[sAa@iBWqAWoAMm@Ow@Q}@u@mEW}Ak@yDAAS}AKo@Ky@KeAK_AEUMiAQ_B?AGg@?EGi@?EGi@AC?AGi@?CGk@ACGk@?CGk@?CGk@ACGo@E[AO?CYiCAEAGEg@Gi@AEGi@?EGi@AEAOCYACGk@?CGk@ACCWCQ?EGi@AEEi@AEGi@?EGi@AEGi@?ECOCYAEGi@?EYgCAGE_@AMGi@?EGi@AEEi@AEAKE]?EGi@AEEi@AEGi@?EGi@AEC]AKAEGo@Q_BK_AGm@W_CK}@}@uI_@cDi@cFqC_ViCaUq@eGm@_Fu@{Ge@eE_AwH[eCGo@Gi@i@cFAQGo@WcC]yCIo@[oCOoAYaC_AmI?Ay@iHwF}e@oA}KUcB[uCYiCAMQ_Bu@oGu@oGg@mEWuBIy@g@eE[mCOoAAUo@mFAGEg@S}AGo@Q_BIo@Im@Go@Ge@AIGo@Io@AIEe@Ge@?IIo@Go@Go@AQE]Go@Go@Go@CWCWGo@CQC]Eo@A??EEi@Go@C_@AO?AGm@C_@AQEe@AIMsBGcAGy@?AAQC[?AM_BA?Eo@?AAKCa@?AEo@Eo@?AEm@?AEm@?ACOC_@Eo@?AEm@?AEm@AAEm@?AEo@C]AQ?AGm@?AEm@Eq@?AEm@[aE?AAMC_@?AGm@?ACa@AK?AEo@?AEm@?A?CIqAAG?CEm@?AGm@?AAKCa@?AEm@?CEm@?AC[AQAAEm@?AEm@?CAQC[A[AMCe@AKCg@AGEk@?CEq@ASAGEi@?EACCe@ACEk@?AC]AOAKAEEi@?EEk@?CGo@Ck@Ca@AOACCk@ACC]AM?CEk@?EEa@?I?CEk@ACAWASACCc@AG?ECk@ACCk@ACEk@?CEm@?AEq@Ek@Gs@Em@?AEm@AAEq@?CEg@?CEo@K_BImAWcD?I_A_N_@kFcAmNCa@c@sGMuBAUSqCS_DIuAKuAUcDEc@OsBYoDMeBMyAEe@I{@QcCOgBSuCGq@K_BSqCEo@Em@Eq@Em@?CGo@Eo@?AEo@Eo@AQE]KaBM_BSqCK_B?AEm@Eq@ACEk@Eo@_@_GCe@Eo@KaBEm@?ACk@?A?AAo@?A?q@Ao@?g@?I?q@?o@?e@?K@m@?C@m@?A?OB_@?A@Y?S?ABo@?A@KBa@@U@WB[?EDe@@IBg@@C?EDg@@GDg@@G@UBS@EN}A?AL_BPeBDi@@CBY@SFo@B[@QD]@OFm@Ba@@G?CDc@@KDc@@I@OB]Fi@?CFm@Dm@@ADm@PcBT_CFi@JyA\\cEXsCF{@h@uFVaD\\yDHs@JmAVuCRuBXmDJuALoBJcBJiBLwBLuBNoCRsD@QL{BPiD^wGPiDRwD^sGFsAP}CPcDPaDB]FmAH_BTyDZiGL_CTcEHkAj@}JH}AVqFB_@LwBXyFh@wJLwBd@wIn@{KXcF\\aGNoCRmD^wGJgB`@qHR_DDu@J{BDcABu@@kB?q@CkACeBGeAEw@CUMsAMoAOqAmAiKMaA_@aDe@eEK{@{@cHKqAKs@K{@QuAIy@UqBQsAIeACQSoCEu@Eq@?GC]Ew@GsBCk@Ck@A]A]CuACcBCkCCwBC}ACgAEuDG{DCoCCoBGmDAyBAk@EwC?SGoDCmCEgDKwIEgCEmDCkCCqEEgEG{IEkFG{H@y@M_OCwCEmDIqKEaGEmE?S?MIwI?c@AqAEeECiDCoDCoEEcGAi@?i@EuFCsCCiCGgHCuDIqKCgGAs@GcIAsACsAOyEOwCAYOmCOaBe@uEc@kDw@gFkAaHiAaHKm@?A_AqFgEiWKq@}CyQKm@o@yDYgBSqAUwAwAkIgIuf@YgBEQgAwGsAcI]sBs@oEwAoIIc@Km@c@iCo@yDKm@}BiNyA{IKi@qA_I{@kFWyAKm@i@wCGc@c@gCy@gFYaBm@uD_CoNo@oD_AwFe@wCcAiGCK?AKm@a@gCq@}DAGi@iDCGg@_DaAaGqAaIe@qCe@wCiDmSo@{D?Ai@aDu@oEAG_AuFEY]mBm@aDWoA[mAQs@GQKa@CGo@sB]cAm@aBeAmCqHyQ_B}Dm@_BSg@Sg@o@_Bu@kBUg@cAeCcAiCq@aBeAmCa@iAk@eBCIk@qBWaAQy@Kg@Qy@Ms@UqAEYKo@Im@EWOiAUmCOqBMkCGqBEiC@}B?E?]?QBsBRuGBo@?MVoIJsEPmFHgCPsFTmHFwAHaD@c@FsCBgCByB?wA?oBCgEAa@EsBCoA?GCaAEaACw@EmAGiAI{AAUQkCKoAEq@I_AOwAO{ASiB[iCWkBKw@CMCOG_@Im@Km@Ii@QcAwAkH]_BEQUiA_B}HMm@gCcM{@cEy@aEaCkLqBuJc@{BAE_@mB_@gBI]qB}JeBqIyBwKaB_I]eBCI{FaYc@qBo@cDi@eCY}AmEaTq@aDAEoByJMm@[{AMm@{Iac@e@_CMk@AIG[AGAGMo@QaAe@_D]uCCYSwBQiCGoAGqAKaDCyD@oBB{ADuBDcAFoA?OPyBR}BNyALkAR_BVeBTyAT}AJo@^eBn@aCd@aBx@gCBK\\eAdBsFX_Ah@iB\\uAJe@PcAPmAHq@H{@LiAH}@?EFeAHwABuABuBBoC@a@D}HB_DJoQ?E?k@?A@{A@sBFoM?K@kFCwBEmBImCOaDW}DW{CQwBc@kFYqDq@{H[uDCSMwAO}AQaBKy@[aCCMSuAa@aCYyAa@mBEQQs@Mi@Y_A_@uAa@sAg@{AY}@GOAESg@iAsCq@_BCGc@eAi@gAEG_@u@iAqBcC{DOUk@u@g@o@i@o@m@u@yBcCKKWYiAeAy@s@IGeA_A_As@o@g@kCqB]W_HiFi@a@sB}Aw@m@sDqC{N_Lw@k@wEoDiG{EcFyDmG{EYUmCwBqBeBu@s@eB_B"
                     },
                     "start_location" : {
                        "lat" : 43.1183195,
                        "lng" : -80.7072723
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 mi",
                        "value" : 961
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 40
                     },
                     "end_location" : {
                        "lat" : 43.2313469,
                        "lng" : -79.9447265
                     },
                     "html_instructions" : "Take exit \u003cb\u003e64\u003c/b\u003e for \u003cb\u003eLincoln M. Alexander Parkway\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "k{yfG`e_gNSa@MQkAmA{@cAQQ_@e@_@g@IIW_@OWO[GMCEKSWm@Si@]oAEM]yA]{AI[COEMYkAEQCCACIIuAaGMm@c@mBGWG]I_@EUEa@EWEa@EWCa@CYAUC_@AW?KAS?]?e@?]@g@B_A@S?QAU"
                     },
                     "start_location" : {
                        "lat" : 43.2275789,
                        "lng" : -79.954894
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "6.8 mi",
                        "value" : 10964
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 416
                     },
                     "end_location" : {
                        "lat" : 43.1964351,
                        "lng" : -79.8207518
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eLincoln M. Alexander Pkwy E\u003c/b\u003e",
                     "polyline" : {
                        "points" : "}rzfGpe}fNHsAPgCv@_MB[`@gGzAyUHaADg@Dk@D[JaBl@qGlAuLb@{D`@_Eh@cFb@mE\\cD^gD@GRiBVsB^uC@OF_@t@yFd@aDXuBZmBD]F]xBeNbBcKb@yCz@iFJs@l@sDJs@bAwGdAwG`BaKfBcLF[F_@F_@dCuOZqBlAqHlAuHT{Ax@iFNw@f@aDBMhBmLHi@Nw@pCgQfEaXLq@@GBSDYdAwG|@yFZmBt@kEzBoNT}ApA{HTyABOr@yEr@wE\\_CZoBfCuPTaBpAkIfAkHN_AVcBxBuND[F[TyAPiANy@NcAPcAvA{I^kCZoBlA}HTwAD[TqAf@eDPgAJm@pAoIx@iFFa@Ly@^cCRiA~@gGh@eDPgAXmBzBwONcAZoBXoBvBkOViBTaBn@yDXuBRuAJs@Hg@BQDWDWDQJk@FWF]Rs@H[Po@Tw@HUL[HWTm@NYTk@LUJWZk@Zk@LSPYNSPWV_@PU^e@PSRWFERUb@c@b@a@x@w@hAeA`@a@|A{AnBmBbAaAjCeCHIlAkAj@c@~@_At@u@r@s@DCn@o@r@u@LODCPU^g@^g@\\k@LSf@}@lAmCTm@Ts@Ts@d@iBRy@TmATuAP_BTsC@]@{@"
                     },
                     "start_location" : {
                        "lat" : 43.2313469,
                        "lng" : -79.9447265
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.8 mi",
                        "value" : 7680
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 306
                     },
                     "end_location" : {
                        "lat" : 43.2476279,
                        "lng" : -79.7643636
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRed Hill Valley Pkwy N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wxsfGt~dfNDyB@mAAyAAc@OwCSyCAGMcA]mB_@gBSu@c@yAY}@Sg@Ui@Wi@Sa@s@qAYc@o@_Ae@i@[][]q@o@cBqAc@WGEa@Wg@Ug@SmAc@OGu@S_Dy@MAeAUeASeAYm@Qe@Qm@Ui@Sg@Wg@Yu@e@y@m@a@_@WW[[]_@?AuBmCs@cA_AoAo@}@}@mAYa@Ya@CCU[Ya@UYq@_Ao@s@s@w@SQACu@o@w@m@KIi@_@{@g@w@a@aA_@sBs@iDeA]KuA_@o@WyHkC}Ao@OEAAi@Se@Si@UwBaAw@_@YOc@U}C{Ai@W}Ay@A?aB_AqAs@_BcAy@g@mAu@_Ai@EE_@U_@WyB}AeCmBqAaA}AsAk@g@WWYYe@m@s@aAU_@OW_@y@Ui@IUu@uBWeA[sA_A{E]kBAEQw@YuAQo@Qi@Wu@Qc@i@qAUe@Yg@Yc@]c@MQ]]g@e@k@a@m@a@[Q]Qw@[{D{As@WqAm@sAq@MKcAu@{@w@s@w@[_@Y]Yc@k@{@QYc@w@]q@Sg@O_@e@sASm@YcAOq@Mm@Oq@Q{@UsAOs@UmAK_@GYQq@I]Uk@}@_CuAcCwBqCu@eA}@iAUW[a@mFwGg@o@UYOOaBuB_C}B[[iDcCiAm@aJeFc@Yc@W_Ak@oAu@qAs@QK_Ak@w@c@IE]OAAOKSOg@YSOSM[SWSQKIIKKQOOQWY[a@WYKQKOOUMSKSA?IQ_@u@Ug@Wm@Qe@Oi@Oi@ACOi@Ou@GWI_@EWAEMm@mAwG"
                     },
                     "start_location" : {
                        "lat" : 43.1964351,
                        "lng" : -79.8207518
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "24.7 mi",
                        "value" : 39704
                     },
                     "duration" : {
                        "text" : "22 mins",
                        "value" : 1292
                     },
                     "end_location" : {
                        "lat" : 43.1778988,
                        "lng" : -79.29017790000002
                     },
                     "html_instructions" : "Take the exit onto \u003cb\u003eQueen Elizabeth Way\u003c/b\u003e toward \u003cb\u003eNiagara\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "ux}fGf~yeNAcAGk@OgAEc@CKAMCWC]CWAYA[@e@@SB[BYDYFUFSFURe@Ti@v@kBPe@Re@d@gAHO\\y@Zu@Ri@Vu@Pk@Lg@BILg@Py@F[BSDYLw@BQBQBOlA_Jf@kDn@iE`@oCpByMx@iFXoBd@wCRwA@GTcBV{Bb@mD?CV}BRcBTgBF]Fi@Ba@CU`ByKJk@XmBb@uCPkAl@eEv@mFpAmIPmAzBcO?EpCyQ^aCvCqRt@cFnAgIz@{Ff@iDrAyIp@oEzCgS~BkOPqArBuMl@eEJm@PiAJq@j@wDd@_DdA}GRsABQ|@}FJo@lAeIZqBf@gDtDmVZsBhAqHHm@x@kFlAgIx@gF^gCn@cEhAqHXmBdBeLn@aEfEuXHo@xAoJvCoR?A\\}BJo@vD{Vz@oFxEi[Jo@Ho@t@{EhAqHf@cDVcBnBuMVcBjCwPj@{Dn@cEF]j@{DHe@|BkO`CuOvAiJt@{ElAaIXmBDY`BwKJk@Hm@T}A`@cCh@sDtCgRnAkIXaBl@{DbB}KvEwZfCwPlEiYhD_U|BaOHo@|BaOzBiOdAqGpAwIHk@`AkGJq@t@_FJm@dA_HD[jByL@InDsUz@qFjCmQ`BmKhHce@fG}`@|AcKD[rC}QBSFYxAuJJo@x@gFPiAtAyI^{BjDoUPoAp@iEPkAd@}CnAgIbAwGpE}YbAyGfBeLp@kExAmJRsAt@yE`@kCdAaHZqBxAmJfAiHj@{D`@yCj@iEl@sENqAJ{@Ho@RkBVaC^eDJgA^_EFq@JgAJiAVqCHcALeBd@sGJgBHwADuADsADuBBaA@}A@gA?{@AwF?aACkXAsN?mAEoUCwc@E}[AaF?sC?o@AsV@oF?mA@oAFyFF}HJmKJeJByBNwPRaRPiQNwNLcLNoK?ED_DHkGJ_ML_LD_FBmBF{GBqCFoGD{CJkM@MBuCF_HH}GDkFHqGLkMDwCFaHP{OD_GLsKNsO@YFuFNcO?a@LiL@q@?G@g@LmL@_A@o@PsO@{@@q@F}FFiGXiXDeFJiJ?UXoXZqYDuDD{EFuF@_A?cBAeCAoCAy@GkJAo@IqKAsCEcGAy@CeC?{@AoA?iB?}@@a@?M?k@@_A@u@BuADqAD_AFuBHyAF}AFk@XcD^{D`AoILaALaAX_BTqA@GDWR_AXwA\\_BVeAZsAZoAZmAt@gCL]BIPk@Ne@p@{BX{@Rm@vCkJJa@tAkE|C{JF[h@cBTy@\\oAd@kBZwAd@qBRcAPiAF_@Lw@Jw@L{@Jw@Hu@NqAJy@?CLkAJsAHqAHyAHqAD}@Bw@?ADoABaA@sABaA@qC?wAAsBC_D?w@GsEEiFIuI?C?m@CcCCcDAq@Ao@AcA?oAAe@EqGAa@AkBIoJCeDAaBAaBAq@C_C?SCgBAoBCyBCuCCyCAo@AeA?{@CiDA}AA{BA_E?mA?gDEeH?_@A{EA{AAkBKyLO}PC_BGwHAkB?cGCk@?eABqA?E@uABgBDiBDoB@a@DkADgADaAHmCBc@Bq@LiDLkDBg@JwC?Cp@iRRcFRwFXyHFkAX}HNiDToGFgAn@oQD{@r@mOTiI"
                     },
                     "start_location" : {
                        "lat" : 43.2476279,
                        "lng" : -79.7643636
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 699
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 43.1738809,
                        "lng" : -79.2850272
                     },
                     "html_instructions" : "Take the \u003cb\u003eON-406\u003c/b\u003e exit toward \u003cb\u003eThorold\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWelland\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003ePort Colborne\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "{dpfGrj}bNTm@?ANcCJyAFy@Fw@Fi@BWFg@F[Lm@FYH]J]HWFQBEJSTe@NWV_@NUPSLMVULKFGROt@]PGTGVGVGZCRCNAl@Ed@CrCMPG"
                     },
                     "start_location" : {
                        "lat" : 43.1778988,
                        "lng" : -79.29017790000002
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "15.7 mi",
                        "value" : 25255
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 905
                     },
                     "end_location" : {
                        "lat" : 42.994374,
                        "lng" : -79.223018
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eON-406 S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wkofGlj|bN~FIn@Cv@Gn@Ih@MXI`@KDARGTKf@Od@Q`@Sd@UROd@[^W`Au@dBuAfAy@v@o@ZUb@[RMNM^Qd@ULEZKr@Wf@Kh@Kv@If@CZAZCZ?b@AX?v@Bt@Bt@Bz@HzAHbCDhCJZ@z@?f@Ab@AXAb@GVE\\GZEf@Mh@O`@ORIx@[b@WTMd@[XOTQ`@]NO`@c@`@c@j@s@\\c@Xe@Vc@PYJWn@wATm@Ro@Rq@XkAPs@Ny@DYBKHi@JeABQDo@Fy@@Y@a@Bu@@c@?Y@w@?]Ag@?i@EqCEkDEmE?GGaFUeOGsDG_FGkFMiLAeAG{GC}BA}@AcC?w@B{@@[@[B_@JuABWDa@D[Jk@Jg@Jg@Nm@H]DSf@yAPa@Xq@Xk@Zg@Ze@RWpFyGl@y@Zg@P]HSLYL]La@No@DOBIFYF]RyAZmBLw@Ly@PuARsARuAHi@DUBOFc@D]Hw@Ba@@Y@g@?k@?EA_@Ca@C[E_@E[G_@Me@ESUs@Ys@Ua@]k@Y[IIWWA?m@a@kAo@A?eAm@}@i@m@[QKUMEC]SaAq@OKu@o@s@y@AAe@o@c@s@]m@c@aAWs@Wy@Qq@Mo@AGAC?AMq@EYEWE]E]Ca@CYCUAa@C]?EAg@?o@?Y?]?[Bw@Fk@Dc@F]RaAJa@HUL]JSPa@P]LUd@s@v@eAb@m@Za@Ze@PWPYP[N[N]Vs@HQDMX{@Pi@N_@h@kB|@sChBaGHSHWRk@Vq@JURa@Zm@T]\\e@TY\\]`@a@`@[j@a@p@_@TOh@Q`@Mn@Sn@SdA[vAa@vBq@nA_@j@S~@YbBi@^Kj@S`Cu@vEwA^OtBs@RIfAg@fAi@r@_@rAw@|BwAfC_BDChAm@XMr@]z@]TIv@Yf@Oh@O|@U`@IdBYxAQd@Eh@Ep@Eb@C\\A\\@~BCp@?dCEjBCtBA~@?Z?b@@@?d@?z@@~@B`AD~@F`AJ`ALzAXlA\\jBj@v@VJF`Bv@zAr@~@f@x@h@n@`@h@d@j@`@v@p@`A~@DB\\\\^`@|@dAZ`@LPLP\\d@v@lAZh@~AdCjB|C~AfCpArBn@dAFHd@r@\\f@h@x@xAnBBBv@bAh@l@nAlAd@f@f@d@v@f@fBlAtAv@jAj@fBz@l@VlAf@vClA~B`AfCdAbCbAn@XjBt@nDzAbCbAj@VbA^j@Tl@RRFXHTF~@Tn@NdAPdANl@FdAHdAFV?R@n@@xA@bDBzABd@?`@@|A@tBBfA@rB?rEFrBBl@?rDDhDDpIFdDBbBBxABt@?z@?`DD|GFrHFj@@~CD`DBT?bDBrGFpFF~A@jB@J?jCB~@?j@?TAT?j@Cj@CTATAh@C~@Il@Gh@GvC_@bEi@`Da@^Gf@GdBSD?pAQdAOtC_@zC_@LC`Dc@~AStAQh@I`AKhBSjBOjBM~@EhBIB?j@C~@C~@A`AAbAAhB?lB?|@?dA@tD?pC@zE@fE@hFBjEBdB@rF@|C@b@@r@?dB@xD@F@Z?~D?pJ@dFBbD@~ODjD@dC@jD?xCBxA@rAAjB@`A?~AB`B?xA?jA@~@?tC@lFBf@?jA?bA@L?z@?d@@x@?D?`@?`A?bA@X?b@?h@?d@?rCBJAF?R?t@@z@@bB?r@?h@AT?TATATALAfAK`@EdAQbASh@Mh@Qx@YHCVKf@Sj@Wr@_@`Am@d@]^WZUZYLKf@c@n@q@NQtAwANQl@w@fNsPnAeBpFyGl@o@`AaAnAeAr@m@pA{@z@i@TMHElAs@h@YpAi@VIp@GnAMf@K^IVCt@?|@D|JGfIMB?nBQnAM~@OlAUXGzAa@|@Wd@O^MLEPId@Q|@_@hAg@hAk@XMtAy@nAy@d@[x@i@`@WVORMd@YHGd@[h@_@d@Yh@[|@k@v@c@v@e@r@]VINIJCLEBA@?B@nA_@VIRETGTGVGRClAU|@KJAj@Eh@Cv@C`BCh@AlB?bA?pEAh@Aj@?V?T?V@V?f@?p@@Z?\\@b@?n@?h@@xA@V?V@T?V?T@T?N@\\BX@R@d@D`@DpCd@xB`@RDJB`@Hl@Lj@JbARt@Nb@JTDVFTDTFTDTDVDPDXFZDf@J`@H`@Fj@Jl@HtGv@b@Hb@Hb@Nb@R`@Vb@\\b@\\TRPNJJFFFDFFB@FDDBDBFBFDLBDBF@F?D@"
                     },
                     "start_location" : {
                        "lat" : 43.1738809,
                        "lng" : -79.2850272
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "482 ft",
                        "value" : 147
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 42.9935892,
                        "lng" : -79.2241636
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e, follow signs for \u003cb\u003eEast Main St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWelland\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "yileGzfpbN@@@@BBF@F?D?F?H?H@J?HBD@FBDB@BBBFJBNDPDZF`@DV@NHl@"
                     },
                     "start_location" : {
                        "lat" : 42.994374,
                        "lng" : -79.223018
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 mi",
                        "value" : 1586
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 180
                     },
                     "end_location" : {
                        "lat" : 42.993035,
                        "lng" : -79.24358280000001
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eE Main St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eNiagara Regional Rd 27\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "}dleG~mpbNBlC?j@?nB@lA?fEDbF?f@DX@~DAnBAtAE~C?b@@lD?hAAzB?V@~CAn@@bA?`B@f@?z@@tB?tA?`A?f@A`D?zA@tF@~D@X?B@V?DF`AhAfKDd@"
                     },
                     "start_location" : {
                        "lat" : 42.9935892,
                        "lng" : -79.2241636
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 393
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 71
                     },
                     "end_location" : {
                        "lat" : 42.9921629,
                        "lng" : -79.24825919999999
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eE Main St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eNiagara Regional Rd 27\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "oaleGjgtbNLbAr@vGFn@@JNrAV~Bz@zH"
                     },
                     "start_location" : {
                        "lat" : 42.993035,
                        "lng" : -79.24358280000001
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "yjjbG`trrPv~Aw}Bx}Bun@{RyhFrcAwlJ|f@atDxfCuh@|jI_dPzeGuqRhzNchShiOa~W`jFcdHfmGo|AbrEgwA|_Fq`Cd}C}TpbB~z@nlDsOtwK~AlzL}pCfiLg[hrGyYtA_hG|`@m{LlkA_sLzk@wkNnZyzQ~iBizU`[ggRhs@olOrBo{SliC{_Vfz@{~MlbIAfqEuUdvBgfBr`HmiLrYeoD}t@{gBhDctLyt@qwNndCyhF|Gwib@fzCsgLd]{wOf`@{~Dk_A}tEfbD_nVvKgx\\wl@ugNbm@elKcgAqcStCmoYlhC{mHzeAsvJ_p@_zRt[}xPaq@wr^_H_iv@aGofSwkBesGqjKqrRmYwlJquA}eB_u@i}C{xAyaI}eAonGmHecG}Qq{MyrAmt@koAmtGs~@}{J`FawIadAs{M{~BitHf]}}E~D{gZrz@qbb@wbB}~SiqBktMkaAcuMwiAoaF{\\_pE_xDutJnCivN{qBeyGglBumCecEwe@q~KeyPkkI}oLogDaeG_|B{`@ewEyaDynCum@{tKm|D{nFmiHg_B}kHevAoiCebF{oCerDs`GeeDa_Fal@urNimAy~ScK{_Rf^omEcw@_`Ewd@etJ}sAccMyW}`OezAauI~AiuUq_E}gKkxAs|_@bjBaxQpQqwJ_lCgqG{}A_gLpQyuOukCkLkxH{}AkiF{z@wsGihCmtC{uJs~GqlJcaIgn@{_BwaBm}Aq`EauEwnJmqB}qDavBgVsgBicBwiJ|HerEmNqsCkiIw}@oqLnyAwmKpiBexJlWsxDy~Ai{DkyBadO}_EodP_yFenNijCeoJ}rBqsIq~Di~Dad@wi^eyBi{Li`DktJku@wtKhq@cnMqm@_vUidAylMp|BocTu@gsHr{@q|FkAsfUluAcwXbs@ixJ\\ibI|c@ksPaOayHvMm{D_kAyuCxMk}Ft`AmnFyc@ypFsaAe`@sc@yyCs^}cBps@_~BdBuiKoBqpx@uDura@}@o{h@Q{kKdtCgkFfwCc_Idx@{}CtiCqjD~pBiyEeWwbEbbA}rF|@e|EuwAmoGkp@uhGuvCw`Fe|@srLcfDsiYky@}zJ_~AksCemL}gRyzGayKg{@esE{sBswXoVabSycAuqGexAa_NgI_zKWa_Rg`DqqQmdAwuOw^gyEebCkiC`dCqcRf`AilC{ZugBwxDuwDssA}yArYkkCxkGqwa@n`AymMvPurQzh@gyK|OgtGllAy]thAe_Fw\\s~@r|AerAjgHz}AdnJgNbzEazAxx@tlD"
         },
         "summary" : "I-80 E",
         "warnings" : [],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
