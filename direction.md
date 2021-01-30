# Direction JSON
From Toronto to Welland

# URL
https://maps.googleapis.com/maps/api/directions/json?origin=toronto&destination=welland&key=AIzaSyAUK9DsZZGaTMMpTshAtchs0St92GpjN7M

# valid response
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJpTvG15DL1IkRd8S0KlBVNTI",
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
               "lat" : 43.6533096,
               "lng" : -79.2199158
            },
            "southwest" : {
               "lat" : 42.9921629,
               "lng" : -79.82935719999999
            }
         },
         "copyrights" : "Map data ©2021 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "134 km",
                  "value" : 134085
               },
               "duration" : {
                  "text" : "1 hour 24 mins",
                  "value" : 5058
               },
               "end_address" : "Welland, ON, Canada",
               "end_location" : {
                  "lat" : 42.9921629,
                  "lng" : -79.24825919999999
               },
               "start_address" : "Toronto, ON, Canada",
               "start_location" : {
                  "lat" : 43.6533096,
                  "lng" : -79.3827656
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 131
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 22
                     },
                     "end_location" : {
                        "lat" : 43.6521792,
                        "lng" : -79.38231689999999
                     },
                     "html_instructions" : "Head \u003cb\u003esouth\u003c/b\u003e on \u003cb\u003eBay St\u003c/b\u003e toward \u003cb\u003eAlbert St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "e`miGhmocNdA[fBg@r@U"
                     },
                     "start_location" : {
                        "lat" : 43.6533096,
                        "lng" : -79.3827656
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1079
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 231
                     },
                     "end_location" : {
                        "lat" : 43.6431829,
                        "lng" : -79.37793119999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eBay St\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "cyliGnjocNHEBCDEBC@C@C@CBC@IBIBKLq@BGBCBE@CBCBCBCDADChBm@hBi@VIlA_@n@U`@MJC|Ag@b@MfA]pBo@`@M`@MBA`@M`@MHC`@OjAa@~B{@TDJEXIb@ORG`@OLE`@M`@M`@Mb@M`@MTITGLEDCPGVILE@?DCLEJG@?LIPK\\KDCDCNEHA"
                     },
                     "start_location" : {
                        "lat" : 43.6521792,
                        "lng" : -79.38231689999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 157
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 36
                     },
                     "end_location" : {
                        "lat" : 43.6423392,
                        "lng" : -79.37949549999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLake Shore Blvd W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{`kiG`oncNRf@Tf@~@vB^x@DJBDHPHR"
                     },
                     "start_location" : {
                        "lat" : 43.6431829,
                        "lng" : -79.37793119999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 138
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 43.6417833,
                        "lng" : -79.3810117
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "s{jiGzxncN@VBV@LBLBLDNFRPd@~@hC"
                     },
                     "start_location" : {
                        "lat" : 43.6423392,
                        "lng" : -79.37949549999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "15.2 km",
                        "value" : 15167
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 578
                     },
                     "end_location" : {
                        "lat" : 43.6095642,
                        "lng" : -79.5547808
                     },
                     "html_instructions" : "Take the ramp onto \u003cb\u003eGardiner Expy W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "cxjiGhbocNRh@Rd@Rj@N\\BHp@fBHRLZDLJZTp@@FHV@DBLNj@Nl@Nh@?@?@FZNt@DPV|@H`@Jp@Nt@Hj@BLFZNjAJ~@Lz@ZxCB\\Lv@PdBPjBPfBPbBJjAHv@Fn@?@J~@JfALpAJdA\\vDJbAJfAHr@?FBT\\nEHx@H`AFx@H`ADp@Bb@@x@@p@Af@@pAAxA?p@An@Ap@A`AExAExA?RExAAvA@p@?H@|@Bx@@l@Bl@@^FrADp@n@jNFfBBx@@d@Bt@@v@B`A@v@?v@?d@?t@?zA?x@?z@?x@@Z?`@@Z@\\@\\@XD|@B\\BXD^BZDZDZDZDZD^FZTpAVpATnA\\rBXzARdAj@`D@B`@xBDPd@dCdA~FZdBLn@VzA`@|BLp@Lp@FZX~AF`@Hf@Lp@PbATjARdAP~@F^PbALl@DXBHNv@F\\N|@Ln@Jl@~@fFZfBLl@Jj@VxADRDVJx@@@BVDZBVB^D`@@ZBX@P@h@@b@@f@@Z?f@?\\A^?XCb@Cn@AVAPC\\Gt@Iz@Ip@AFYbB]~Aa@vAK`@IRw@`CIXUr@Yz@O\\Uv@W|@sBhGmAvDGR{@hCsCxIcA|CCFM`@Ut@Of@Mb@Wz@Mf@Md@Sv@Kj@Qt@WfAOv@Mt@Q`AOx@UrAQlAEZOfAOlAABQ~AQ`BKlAMzAKnACb@?BEf@?BIhAGpAEbAGpACt@E`ACnA?PCp@?LEfCA`B?X?N?|@?R?L@b@?J?d@?ZBrA@d@@Z?RD`AF`BHrAHdAF|@Fp@JjAP`BFj@Hp@Fl@L`A@BHr@Hh@Hd@@HFb@Jj@ZfBPx@Hd@BHH`@DPZpAXjAPp@t@nCj@jBTr@n@nBt@xB`AxCr@tBVn@L\\LXLVl@nARb@p@vA^t@f@`ANZh@~@d@~@FJf@bALXNZHRXl@^~@d@hA\\z@Pf@Zt@FLJV\\r@@?\\p@l@dAd@v@j@|@V`@`@l@bA~Al@`AV^V`@HLLNLPT\\JNLNX^Zb@n@|@p@`ALN`@j@\\f@l@|@Zf@\\j@\\n@JRLZVl@Tl@JZHXHVHZPp@Nr@H\\ZhBfA~GZtBd@zCLt@FZNbAV|AXbBRxADNj@|DzAvJl@|D\\vBtBjN`ApGv@jFJl@lAhIjBfNBTdBzMp@`G@BBH@D@HFf@LhAJx@`@fD?F`AjIFj@~CbXv@zGNvADb@LdAz@xHr@dG\\xCRdBv@`Hl@hFf@lEhArJBXFd@V~BrApLn@nFNtADXHx@p@`Gn@~FFh@ZnCZlC`@jDP~Al@xET`B?@ZnCFp@VpCH|@JrAJdAHpAPbCJhBFn@NfCf@nHLjBJ|A@L@PH|@Db@Hr@Db@Hl@Fd@N~@DXRdATdALf@Rv@Pn@J\\Tt@Zx@b@lAb@`Aj@lAj@bAt@lAb@l@V\\h@r@xAdB|@`AtDjEtB~B"
                     },
                     "start_location" : {
                        "lat" : 43.6417833,
                        "lng" : -79.3810117
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "17.1 km",
                        "value" : 17141
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 586
                     },
                     "end_location" : {
                        "lat" : 43.4858182,
                        "lng" : -79.67305619999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eQueen Elizabeth Way\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wndiGj`qdNvAhBlBzB|BdCjAtAnAvAbHbINPJLx@`Af@l@nAtANRvAzAhBnBnBxBZ\\pBzBb@d@tB`C^b@rBfCnDzDdAlA~BjCjD~DhCtC?@Z\\Z\\|BhCjBpB~DpEf@j@pFdG\\^`FvFx@z@jKlL~AdBfAnAJJ~AdBdAlAlH`IzCdDlDzDdH~HpAxAx@|@r@z@`@b@|JhL|HxIp@t@tCdD`EpEtB`C^^fApAdAjAzBdC|@bAt@z@dAnA~AlBX\\lCzCdBlBnAvAfAlAd@h@dDtDd@h@LL`BjBfBlBHJfAlAdAhAZ^Z\\RR~BjCvA|AjApADFjBrB~@bA`AbAfAjApAvAr@v@f@f@p@p@^\\ZX\\XPLVRr@f@r@d@b@Zj@\\rBtA~AdAjAv@TLbAp@rAz@hAv@f@\\jAv@v@h@nBnAnAz@p@d@`@Xb@Z\\TVPbAp@hBjAbBhATLh@\\p@b@f@\\DBp@d@x@j@d@\\b@\\f@`@\\X`@^v@v@dAhANR^d@V\\PTPVNTLR^l@j@dAZl@f@`ANZb@fAXr@Tn@JXTt@`@nA^pAFTVt@Tr@`@jAL\\Ph@N\\Tj@d@hAf@fAJVPZVj@Zn@Zj@b@v@`AbBJPl@bAlAjBtAlBd@l@r@x@p@v@l@r@v@z@`@b@t@x@p@v@t@x@^`@p@t@vA|AfBpB`BhB@BXXnC|CrB|BzBdCrB~BjDzDtAzAn@t@~ClDpAvA`BhB`@b@tA~At@x@lAtAfBpBLNZ\\nD~DjArA`EpEhDvDX\\zDlE|H`JDDnB|Bx@~@bAhAVX`BjBdAlAZ^vA~AnAtA`AfAn@r@zAhBn@r@v@|@t@|@n@r@n@p@zCfDbAfA`BdBp@r@tC~CtB~B`ClCFFlCzCz@bAv@z@`BhB`AhA|AhBh@l@HHRVhBpBx@~@xAbBFHlBvBxChDZ\\fAnAxBdCzMfOt@z@z@~@`FvFZ\\x@|@`FvFhDxDdJpKZ^TXnHvIl@n@~@hAf@h@VZh@h@X\\b@\\d@`@XR^Z^T^TXNTLZNXJXHz@X|@NVBh@F^Fb@Dl@@`BAzCAlG]fAIjDKz@AD?N?p@A|ACrACV?tBGnM]xDMhGQrDKX?rGM"
                     },
                     "start_location" : {
                        "lat" : 43.6095642,
                        "lng" : -79.5547808
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "20.5 km",
                        "value" : 20513
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 705
                     },
                     "end_location" : {
                        "lat" : 43.3415121,
                        "lng" : -79.8233292
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eQueen Elizabeth Way\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-403 W\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "kilhGrcheNzPe@hN]^Ap@AnGSd@Az@CvCEf@?z@?d@@rBHf@Bd@DJ@dAHtC\\zB`@z@PrA\\h@Nh@NtBt@pAd@jAf@~At@|@h@bBbAvA|@x@l@xAhALJl@h@~@z@fAfA|@~@@@jEzEvC~CdFvFHHLTfChC|GtH`FpFx@~@`@d@t@x@t@z@b@d@`BjB@?vA|A^`@b@h@rAtAJLdArAxBfCbBlB`AhA|@`Ar@x@n@v@NPv@|@b@d@l@v@n@x@z@hA`AlAbAnAp@r@zAbBnApAbAjA`AjAjBzBTZTZb@f@fC|BVZJJp@p@xB`CzA`Bp@r@l@n@vB~B@@|G~Hp@z@n@z@zBjCtBhC`CnCdD|Dt@|@nA|AfE|En@t@pCzC|CpDVXBB`AhA|AfBBDhCzCl@r@lCzCdE~EhBlBvBdCvBbCpC`DzAbB|I`KTb@nD|D|BnClHnIlGjHzJ`LrFlGvDbELPtAxAhApAfGzGdCvCx@dA~DtE~@dAtFnG~KhM`@f@jAvAdAlAzA`BjArAz@bAbIhI|D~Dx@z@x@z@RTbAfA`BfB~@bAbAjAnAtAn@v@zBfCf@l@^`@hBpBVZjCdDlAzArA`BnC`DxBdCdDpDt@z@f@d@vDfEzAbBlArAjArAb@d@jFxFpTlVvA|A~BhCpD~DdCnCPRtCbDtAzAvBbCdDpDvB~B|@`A|AdBnCzCtAzA`AdArC~CbDrDdBnBz@~@dAjArC`DzChDfCtChCrCrB`ChEzEhDrD|ClDpBxBrAzAb@f@d@f@lAtAfAlAdBlBfBpBhBrB~AjBtB`ChCtCfBtBdCnCdBpBzBfC~@dAhApAf@j@TThCxCtA|AdAlAbBnBxCfDhApAbOxPt@|@fE|E`IbJlC~C`O|PvBbCtJvK`BjB`@f@f@h@~FvGrCdDhAjAtAzAvBbCrA`Bp@|@|@lA|AtBxBvDx@~Af@z@\\r@d@~@`AvBr@`B|@zBnAdD~BjGbAnCZ~@~B`H|EvNXv@|@dCh@|AjAbDv@vBzAjEZx@Pb@@Bx@jC"
                     },
                     "start_location" : {
                        "lat" : 43.4858182,
                        "lng" : -79.67305619999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "51.7 km",
                        "value" : 51679
                     },
                     "duration" : {
                        "text" : "28 mins",
                        "value" : 1683
                     },
                     "end_location" : {
                        "lat" : 43.1778988,
                        "lng" : -79.29017790000002
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork to continue on \u003cb\u003eQueen Elizabeth Way\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eQEW\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "mcpgGxnefNj@v@l@dB`AlCt@jBp@dBNVFL\\n@n@hA`@j@^f@z@dA|@|@b@`@h@`@h@`@^V\\R\\PHF^NNHbA`@n@R|@Tj@J~@L~@Jt@D`A@D?~@Cb@Av@Gn@In@Mf@Kf@M^K\\Mj@Sl@W~@c@t@]DCl@Yh@Wx@]tAo@~@c@TI\\KZGJIdAg@ZO\\Ox@a@j@Y`@S^SnAu@vBoAJIJIXSXQr@o@XWv@y@bBiBjAsApB}BFMjA}A`B}BbCiEpA_CrByDn@mA`CqEv@wAjAyBnCeFLWdAoBdAmBZm@\\q@pBqDvB_ERa@@Cn@iAVe@DKNYj@cABEVe@p@qAzAyCrAgCXm@n@oARc@\\q@PWLUVe@HM`@s@^k@d@o@BEZa@TYPU`@a@l@k@TW@?ZYPOLI\\WBAZS^U?A`@SXONIVKRILG\\Mn@UVIn@SxAa@b@MbAYTGfBg@n@SDCXMTIJE`@QRILGjHeDx@_@pBgA~Ao@dBy@bBy@`@Qf@WXM`@SbCkA~@e@@?`@S`Ae@XOzAu@\\O\\Q|BgA\\S@A^SxHsDHEh@W^Qn@[r@]^Sn@Yr@]pBaAVMZO`@SjKiF`@S`JmETKPId@WbCkA`Ae@bAg@^QtDiB`@S`@SdEqBxDkBvDgBBAp@]n@[fEoBlEqBzAq@`DkA`KyDtDwAbDmANG`@OHCVKjAe@j@Yb@WlAs@t@k@`@]TQHGTSd@c@tBoBh@g@l@k@\\]zCuChCcCf@e@lCgCtFkF|EsEdC_C`C}BLK|DuDBCfBeBx@u@r@o@j@g@dD}C\\[nAiAfF}E|A{AfE}D\\]DENQLKDEp@q@`CwBfDqCdAs@TS~@o@ROhAu@^WNKNIrBqAJGb@YROFC~ByA|AcArAy@zDcChCaB`Ak@bDqBpEoCzDcCdBgA|BwAp@a@^UfBkAZWz@k@x@g@lAs@hC_Bx@i@d@_@`@_@b@c@h@o@f@q@`@k@h@}@Xm@Zo@Vq@Vo@Ts@Le@Po@Ns@Ns@PaAPmA`@mC\\}Bb@{CbAyG\\{BL}@zB{NzA_Kx@mFrA}I`ByK`ByKJk@XmBb@uCPkAl@eEv@mFpAmIPmAzBcO?EpCyQ^aCvCqRt@cFnAgIz@{Ff@iDrAyIp@oEzCgS~BkOPqArBuMl@eEJm@PiAJq@j@wDd@_DdA}GRsABQ|@}FJo@lAeIZqBf@gDtDmVZsBhAqHHm@x@kFlAgIx@gF^gCn@cEhAqHXmBdBeLn@aEfEuXHo@xAoJvCoR?A\\}BJo@vD{Vz@oFxEi[Jo@Ho@t@{EhAqHf@cDVcBnBuMVcBjCwPj@{Dn@cEF]j@{DHe@|BkO`CuOvAiJt@{ElAaIXmBDY`BwKJk@Hm@T}A`@cCh@sDtCgRnAkIXaBl@{DbB}KvEwZfCwPlEiYhD_U|BaOHo@|BaOzBiOdAqGpAwIHk@`AkGJq@t@_FJm@dA_HD[jByL@InDsUz@qFjCmQ`BmKhHce@fG}`@|AcKD[rC}QBSFYxAuJJo@x@gFPiAtAyI^{BjDoUPoAp@iEPkAd@}CnAgIbAwGpE}YbAyGfBeLp@kExAmJRsAt@yE`@kCdAaHZqBxAmJfAiHj@{D`@yCj@iEl@sENqAJ{@Ho@RkBVaC^eDJgA^_EFq@JgAJiAVqCHcALeBd@sGJgBHwADuADsADuBBaA@}A@gA?{@AwF?aACkXAsN?mAEoUCwc@E}[AaF?sC?o@AsV@oF?mA@oAFyFF}HJmKJeJByBNwPRaRPiQNwNLcLNoK?ED_DHkGJ_ML_LD_FBmBF{GBqCFoGD{CJkM@MBuCF_HH}GDkFHqGLkMDwCFaHP{OD_GLsKNsO@YFuFNcO?a@LiL@q@?G@g@LmL@_A@o@PsO@{@@q@F}FFiGXiXDeFJiJ?UXoXZqYDuDD{EFuF@_A?cBAeCAoCAy@GkJAo@IqKAsCEcGAy@CeC?{@AoA?iB?}@@a@?M?k@@_A@u@BuADqAD_AFuBHyAF}AFk@XcD^{D`AoILaALaAX_BTqA@GDWR_AXwA\\_BVeAZsAZoAZmAt@gCL]BIPk@Ne@p@{BX{@Rm@vCkJJa@tAkE|C{JF[h@cBTy@\\oAd@kBZwAd@qBRcAPiAF_@Lw@Jw@L{@Jw@Hu@NqAJy@?CLkAJsAHqAHyAHqAD}@Bw@?ADoABaA@sABaA@qC?wAAsBC_D?w@GsEEiFIuI?C?m@CcCCcDAq@Ao@AcA?oAAe@EqGAa@AkBIoJCeDAaBAaBAq@C_C?SCgBAoBCyBCuCCyCAo@AeA?{@CiDA}AA{BA_E?mA?gDEeH?_@A{EA{AAkBKyLO}PC_BGwHAkB?cGCk@?eABqA?E@uABgBDiB@o@B_A@a@DkADgABq@@OHmCBc@?ABo@LiDH{BBo@Bg@JwC?Cp@iRRcFRwFXyHFkAX}HNiDToGFgAn@oQD{@r@mOTiI"
                     },
                     "start_location" : {
                        "lat" : 43.3415121,
                        "lng" : -79.8233292
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
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
                        "text" : "25.3 km",
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
                        "text" : "0.1 km",
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
                        "text" : "1.6 km",
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
                        "text" : "0.4 km",
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
            "points" : "e`miGhmocNzFqBb@eBvOqFhJuCvFqB~AYnFcBxBs@~As@d@OhC`Gh@bC~C|IfEtMzAlH~AtMzEnf@pAxOJfMY|OVbKlAt[@vM~@pNzKnm@lNzw@\\fF?jGi@bHeB|HaBbF}InXuH~UcC|KqBrMsAjOm@|NCpTr@|MpArL`BpJ|DhOdHtSbGvL|IdSnMnSrGdJjDjHlDzQlDbUhMdz@fJ`r@|NdpAbOzqAfFnc@fB~RxBl\\bA~IdChKnCvG|C|EpXr[lSvUhl@tp@zw@r|@fsBb~B|^fa@pGdGlNhJl_@|VpH`FxHtH`EvGnEhLfDbKpExJ|KrPvJxKhn@lr@lqAryAf}AveB`e@ni@fG|FzFhC~Cb@nIBbV{@bi@uA|v@oBnNPrKzA|GrBzHlDnIxFfRvR`^n`@f]d`@vJvLhPhRlN~NtUhXbm@zr@dyCriDnZj[hO~PzX~[fm@~p@fy@|}@lw@l|@riC`xCnZv]xHhMxDlIdVnq@vJlXtEvL~BvFnClEfEfEbGbDxEbA|DRjEW~Cs@jIqDpJaEhLiGtHeHpG}HjLaS~Qm]`KgR|N_YpEiGbDqCrDoBdJsCpGwBbXcM~V}Ljg@oV`q@_\\`PoH|ZkL|HsDni@eg@xo@qm@jMyKfJiGlq@gb@jPkKtCsClCiE`DcKvFk_@j]q}Bfd@cyCnz@_uFvyCu|R`b@_oCrLuv@tG{e@vC_ZvBy\\F_o@SmvB@ac@f@kh@fBocBvBmyBlHifHEec@Y_f@NwL^mJbC{U`CmNpEgQzJq[jJ{\\jBgMrAmPZqP]{d@m@}w@c@yq@u@{yAv@sZ~GujBdBa]b@yGbAcHjB_EfDoCdEo@jMc@`Ec@zEaBfLoIrEgC|Dy@zBI|Nb@hGJxBQ~GyB`FaEzBaDbBwDvBkJf@wIQmUeA_z@GgWbAgIhDaJnIqKdAsBxA{G`C_Pb@yGk@eFkA}CyAiBaIqEuFmEiBsCeBaFq@_EY}EXiHtBaGnF}H`Lu\\bBsCvBuB|CcBfEqAzPkFnNqEvE{BrPkJ~CcA~GkArKYnOI|FRlHpApGbCdGfDpIbItJfOpLpQtDbElFbEdXtLnV`KlJtBrOb@||@x@vfA|@zGM~UqCjRaCdWqC~M]fa@FdxAb@fx@TtWFdJ@bI_AvHuCdHuFz^wc@vGqFhDqBdEuAnDg@xXObGo@fJeC|McHfG}DxI}E~Cy@zGeA~ZMvNRfVlEtEz@pKtAnCv@lDpC|@d@pBXj@xA^nNDvu@Plh@~Fti@"
         },
         "summary" : "Queen Elizabeth Way/QEW",
         "warnings" : [],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
