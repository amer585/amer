--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.9) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then local v89=0;while true do if (v89==0) then v19=v0(v3(v30,1,1));return "";end end else local v90=v2(v0(v30,16));if v19 then local v113=v5(v90,v19);v19=nil;return v113;else return v90;end end end);local function v20(v31,v32,v33) if v33 then local v91=(877 -(282 + 595)) -0 ;local v92;while true do if (v91==(0 -0)) then v92=(v31/((3 -1)^(v32-1)))%(2^(((v33-1) -(v32-(2 -1))) + 1)) ;return v92-(v92%1) ;end end else local v93=(2256 -(1523 + 114)) -(555 + 64) ;local v94;while true do if (v93==(931 -(857 + 67 + 7))) then v94=(570 -(367 + 201))^(v32-(928 -(214 + 713))) ;return (((v31%(v94 + v94))>=v94) and (1 + 0)) or (0 + (0 -0)) ;end end end end local function v21() local v34=v1(v16,v18,v18);v18=v18 + 1 ;return v34;end local function v22() local v35=1065 -(68 + 997) ;local v36;local v37;while true do if (v35==0) then v36,v37=v1(v16,v18,v18 + (1272 -(51 + 175 + 1044)) );v18=v18 + 2 ;v35=4 -3 ;end if (v35==(118 -(32 + 85))) then return (v37 * (251 + 5)) + v36 ;end end end local function v23() local v38,v39,v40,v41=v1(v16,v18,v18 + (960 -(892 + 65)) );v18=v18 + (9 -(355 -(87 + 263))) ;return (v41 * 16777216) + (v40 * (121138 -55602)) + (v39 * (469 -213)) + v38 ;end local function v24() local v42=v23();local v43=v23();local v44=1;local v45=(v20(v43,(199 -(10 + 8)) -((257 -190) + 113) ,20) * ((2 + 0)^((78 + 0) -46))) + v42 ;local v46=v20(v43,16 + 5 ,31);local v47=((v20(v43,127 -(886 -(368 + 423)) )==(953 -(802 + 150))) and  -(2 -1)) or (1 -0) ;if (v46==((442 -(416 + 26)) + 0)) then if (v45==(997 -(915 + 82))) then return v47 * (0 -0) ;else v46=1;v44=0 + 0 ;end elseif (v46==((8592 -5901) -644)) then return ((v45==(1187 -(1069 + 51 + 67))) and (v47 * ((2 -(1 -0))/(0 -0)))) or (v47 * NaN) ;end return v8(v47,v46-(178 + 845) ) * (v44 + (v45/(2^((288 -196) -40)))) ;end local function v25(v48) local v49;if  not v48 then local v95=430 -(44 + 386) ;while true do if (v95==(1486 -(998 + (2031 -1543)))) then v48=v23();if (v48==(772 -(118 + 83 + 571))) then return "";end break;end end end v49=v3(v16,v18,(v18 + v48) -(1 + 0) );v18=v18 + v48 ;local v50={};for v66=1139 -((423 -307) + 1022) , #v49 do v50[v66]=v2(v1(v3(v49,v66,v66)));end return v6(v50);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v51=(function() return function(v96,v97,v98,v99,v100,v101,v102,v103,v104) local v105=(function() return 0 -0 ;end)();local v96=(function() return;end)();local v97=(function() return;end)();while true do if (v105==1) then local v118=(function() return 578 -(386 + 192) ;end)();while true do if (v118~=(1206 -(696 + 510))) then else while true do if (v96==(0 -0)) then v97=(function() return v98();end)();if (v99(v97, #"{", #"\\")==0) then local v125=(function() return 867 -(550 + 317) ;end)();local v126=(function() return;end)();local v127=(function() return;end)();local v128=(function() return;end)();while true do if (v125~=(1262 -(1091 + 171))) then else v126=(function() return v99(v97,1 + 1 , #"asd");end)();v127=(function() return v99(v97, #"0836",18 -12 );end)();v125=(function() return 286 -(134 + 151) ;end)();end if ((1668 -(970 + 695))==v125) then if (v99(v127, #"asd", #"asd")~= #">") then else v128[ #"0313"]=(function() return v102[v128[ #".dev"]];end)();end v103[v104]=(function() return v128;end)();break;end if (v125~=(3 -2)) then else local v184=(function() return 0;end)();while true do if (v184==(1990 -(582 + 1408))) then v128=(function() return {v100(),v100(),nil,nil};end)();if (v126==0) then local v469=(function() return 0;end)();local v470=(function() return;end)();while true do if (v469==(0 -0)) then v470=(function() return 0;end)();while true do if (v470==(0 -0)) then v128[ #"91("]=(function() return v100();end)();v128[ #".com"]=(function() return v100();end)();break;end end break;end end elseif (v126== #"[") then v128[ #"91("]=(function() return v101();end)();elseif (v126==2) then v128[ #"xxx"]=(function() return v101() -((376 -(123 + 251))^16) ;end)();elseif (v126~= #"-19") then else local v509=(function() return 1824 -(1195 + 629) ;end)();local v510=(function() return;end)();while true do if ((0 -0)~=v509) then else v510=(function() return 0;end)();while true do if ((698 -(208 + 490))==v510) then v128[ #"xnx"]=(function() return v101() -((782 -(162 + 618))^(2 + 14)) ;end)();v128[ #"asd1"]=(function() return v100();end)();break;end end break;end end end v184=(function() return 1;end)();end if ((1 + 0)~=v184) then else v125=(function() return 3 -1 ;end)();break;end end end if (v125==2) then if (v99(v127, #"!", #",")== #"~") then v128[838 -(660 + 176) ]=(function() return v102[v128[1 + 1 ]];end)();end if (v99(v127,2,204 -(14 + 188) )== #"}") then v128[ #"asd"]=(function() return v102[v128[ #"gha"]];end)();end v125=(function() return 678 -(534 + 141) ;end)();end end end break;end end return v96,v97,v98,v99,v100,v101,v102,v103,v104;end end end if (v105~=(1636 -(1373 + 263))) then else local v119=(function() return 1000 -(451 + 549) ;end)();local v120=(function() return;end)();while true do if (v119~=(0 + 0)) then else v120=(function() return 0 + 0 ;end)();while true do if (0==v120) then v96=(function() return 0;end)();v97=(function() return nil;end)();v120=(function() return 1 + 0 ;end)();end if (v120~=(1 -0)) then else v105=(function() return 1;end)();break;end end break;end end end end end;end)();local v52=(function() return function(v106,v107,v108) local v109=(function() return 0 -0 ;end)();while true do if ((0 -0)==v109) then v106[v107-#"[" ]=(function() return v108();end)();return v106,v107,v108;end end end;end)();local v53=(function() return {};end)();local v54=(function() return {};end)();local v55=(function() return {};end)();local v56=(function() return {v53,v54,nil,v55};end)();local v57=(function() return v23();end)();local v58=(function() return {};end)();for v68= #"<",v57 do local v69=(function() return 0;end)();local v70=(function() return;end)();local v71=(function() return;end)();local v72=(function() return;end)();while true do if (v69~=1) then else v72=(function() return nil;end)();while true do if (v70~=(0 -0)) then else local v122=(function() return 0 -0 ;end)();local v123=(function() return;end)();while true do if (v122==0) then v123=(function() return 0 + 0 ;end)();while true do if (v123==(0 + 0)) then v71=(function() return v21();end)();v72=(function() return nil;end)();v123=(function() return 1 -0 ;end)();end if (v123~=(397 -(115 + 281))) then else v70=(function() return 1;end)();break;end end break;end end end if (v70~=(1582 -(1535 + 46))) then else if (v71== #">") then v72=(function() return v21()~=0 ;end)();elseif (v71==(2 + 0)) then v72=(function() return v24();end)();elseif (v71~= #"-19") then else v72=(function() return v25();end)();end v58[v68]=(function() return v72;end)();break;end end break;end if (v69==0) then v70=(function() return 0;end)();v71=(function() return nil;end)();v69=(function() return 2 -1 ;end)();end end end v56[ #"19("]=(function() return v21();end)();for v73= #"{",v23() do FlatIdent_4D434,Descriptor,v21,v20,v22,v23,v58,v53,v73=(function() return v51(FlatIdent_4D434,Descriptor,v21,v20,v22,v23,v58,v53,v73);end)();end for v74= #"}",v23() do v54,v74,v28=(function() return v52(v54,v74,v28);end)();end return v56;end local function v29(v60,v61,v62) local v63=v60[(1403 -(832 + 570)) + 0 ];local v64=v60[2 + 0 ];local v65=v60[563 -(306 + 254) ];return function(...) local v75=v63;local v76=v64;local v77=v65;local v78=v27;local v79=1;local v80= -(1 + 0 + (0 -0));local v81={};local v82={...};local v83=v12("#",...) -(1 -0) ;local v84={};local v85={};for v110=1467 -((1695 -(588 + 208)) + 568) ,v83 do if (v110>=v77) then v81[v110-v77 ]=v82[v110 + (2 -1) + 0 ];else v85[v110]=v82[v110 + (2 -1) ];end end local v86=(v83-v77) + (604 -(268 + 335)) ;local v87;local v88;while true do v87=v75[v79];v88=v87[291 -(60 + 230) ];if (v88<=(625 -(426 + 146))) then if (v88<=(4 + 22)) then if (v88<=(1468 -(282 + 1174))) then if ((v88<=5) or (1696<=1059)) then if (v88<=2) then if (v88<=0) then local v129=v87[813 -(569 + 242) ];local v130={};for v172=2 -1 , #v84 do local v173=0 + 0 ;local v174;while true do if (v173==0) then v174=v84[v172];for v404=1024 -(706 + 318) , #v174 do local v405=0;local v406;local v407;local v408;while true do if ((2343==2343) and (v405==(1252 -(721 + 530)))) then v408=v406[1273 -(945 + 326) ];if ((v407==v85) and (v408>=v129)) then local v498=0 -(1800 -(884 + 916)) ;while true do if (v498==0) then v130[v408]=v407[v408];v406[1 + (0 -0) ]=v130;break;end end end break;end if (v405==0) then v406=v174[v404];v407=v406[1];v405=701 -(271 + 429) ;end end end break;end end end elseif ((v88>(1 + 0)) or (1043>3591)) then local v185=1500 -(1408 + 92) ;local v186;while true do if (v185==(1086 -(461 + 625))) then v186=v87[1290 -(993 + 295) ];v85[v186](v85[v186 + 1 ]);break;end end else v85[v87[1 + 1 ]]= #v85[v87[3]];end elseif ((v88<=(1174 -(418 + 753))) or (2890>=4079)) then v79=v87[2 + 1 ];elseif ((4474<=4770) and (v88==4)) then v85[v87[2]]=v87[1 + 2 ];else v85[v87[2]]=v85[v87[1 + 2 ]]%v85[v87[2 + 2 ]] ;end elseif ((v88<=(5 + 3)) or (4942==3903)) then if (v88<=6) then v85[v87[531 -(406 + 123) ]]=v85[v87[1772 -((2402 -(232 + 421)) + 20) ]]/v87[1 + 3 ] ;elseif (v88==7) then local v191=0;local v192;local v193;while true do if ((v191==(1322 -(1249 + 73))) or (248>4845)) then v192=v87[3];v193=v85[v192];v191=1;end if (v191==(1 + 0)) then for v449=v192 + (1146 -(466 + 679)) ,v87[1893 -(1569 + 320) ] do v193=v193   .. v85[v449] ;end v85[v87[4 -2 ]]=v193;break;end end else v85[v87[5 -3 ]]= not v85[v87[1903 -(106 + 1794) ]];end elseif ((1569==1569) and (v88<=(4 + 6))) then if (v88==(3 + 6)) then local v195=0 -0 ;local v196;local v197;local v198;while true do if ((v195==((1 + 1) -1)) or (4927<=3221)) then v198=114 -(4 + 110) ;for v450=v196,v87[588 -(57 + 527) ] do local v451=1427 -(41 + 1386) ;while true do if (v451==(103 -(17 + 86))) then v198=v198 + 1 + 0 ;v85[v450]=v197[v198];break;end end end break;end if (v195==(0 -0)) then v196=v87[2];v197={v85[v196](v13(v85,v196 + 1 ,v80))};v195=1;end end else v85[v87[5 -3 ]]=v87[169 -(122 + 44) ]~=((0 + 0) -0) ;end elseif (v88>(36 -25)) then local v200=v87[(6 -4) + (605 -(316 + 289)) ];local v201,v202=v78(v85[v200](v13(v85,v200 + 1 ,v87[(2 -1) + 2 ])));v80=(v202 + v200) -(1 -0) ;local v203=(4 + 61) -(30 + 35) ;for v339=v200,v80 do v203=v203 + 1 + 0 ;v85[v339]=v201[v203];end elseif ( not v85[v87[2]] or (1780>2787)) then v79=v79 + (1258 -(1043 + 214)) ;else v79=v87[11 -8 ];end elseif (v88<=((2684 -(666 + 787)) -(323 + 889))) then if ((v88<=(40 -25)) or (3937<=1230)) then if (v88<=(593 -(361 + 219))) then local v133=320 -((478 -(360 + 65)) + 267) ;local v134;local v135;local v136;local v137;while true do if (v133==(1 + 0 + 1)) then for v386=v134,v80 do local v387=413 -(15 + 398) ;while true do if (((982 -(18 + (1218 -(79 + 175))))==v387) or (2637<1706)) then v137=v137 + 1 ;v85[v386]=v135[v137];break;end end end break;end if (v133==(3 -2)) then v80=(v136 + v134) -(1 + 0) ;v137=0 -0 ;v133=2 + 0 ;end if (v133==(850 -(16 + 4 + 830))) then v134=v87[(5 -3) + 0 ];v135,v136=v78(v85[v134](v13(v85,v134 + (127 -((223 -107) + 10)) ,v80)));v133=1;end end elseif ((v88==(2 + 12)) or (2669<=2409)) then local v204=(1637 -(503 + 396)) -(542 + 196) ;local v205;while true do if (v204==((181 -(92 + 89)) -0)) then v205=v87[2];v85[v205]=v85[v205](v85[v205 + 1 + 0 ]);break;end end else v85[v87[2 + 0 ]]=v87[(3 -1) + 1 ] + v85[v87[10 -(4 + 2) ]] ;end elseif (v88<=(43 -(16 + 10))) then if (v88==(1567 -(1126 + 425))) then v85[v87[2]]=v85[v87[408 -((462 -344) + 287) ]][v85[v87[(3 + 12) -11 ]]];else v85[v87[1123 -(118 + 1003) ]]={};end elseif (v88>(52 -34)) then v85[v87[2]]=v61[v87[380 -(142 + 235) ]];else v85[v87[(20 -11) -7 ]]=v87[1 + 2 ] + v85[v87[4]] ;end elseif (v88<=(999 -(553 + 424))) then if (v88<=(18 + 2)) then if ((v85[v87[3 -1 ]]~=v85[v87[4 + 0 ]]) or (1401>4696)) then v79=v79 + 1 ;else v79=v87[3 + 0 ];end elseif (v88>(13 + 8)) then if ((v87[1 + 1 ]==v85[v87[3 + 1 ]]) or (3280<1321)) then v79=v79 + (2 -1) ;else v79=v87[7 -4 ];end else v85[v87[4 -2 ]]= not v85[v87[3]];end elseif (v88<=(7 + 17)) then if ((4927>=2303) and (v88==23)) then v85[v87[9 -7 ]]=v85[v87[3]];else local v217=753 -(239 + 514) ;local v218;while true do if ((3462>=1032) and ((0 + 0)==v217)) then v218=v87[1331 -(797 + 532) ];v85[v218]=v85[v218]();break;end end end elseif (v88==(12 + 13)) then local v219=0 + 0 ;local v220;while true do if (v219==(0 + 0)) then v220=v87[2];v85[v220]=v85[v220](v13(v85,v220 + 1 ,v87[3]));break;end end else v85[v87[4 -2 ]]=v85[v87[3]]/v87[1206 -(373 + (2524 -1695)) ] ;end elseif (v88<=(770 -(476 + 255))) then if (v88<=(1162 -(369 + 761))) then if ((v88<=(17 + 12)) or (1077>=2011)) then if (v88<=(48 -(3 + 18))) then local v138=0;local v139;local v140;local v141;local v142;while true do if ((0 -0)==v138) then v139=v87[240 -(64 + 174) ];v140,v141=v78(v85[v139](v85[v139 + 1 + 0 ]));v138=1;end if ((1543<2415) and (v138==(1 -0))) then v80=(v141 + v139) -(337 -(144 + 192)) ;v142=(329 -113) -(42 + 174) ;v138=(1246 -(485 + 759)) + 0 ;end if ((v138==(2 + 0)) or (4444<2015)) then for v389=v139,v80 do local v390=0 + 0 ;while true do if (v390==((3479 -1975) -(363 + 1141))) then v142=v142 + (1581 -(1183 + 397)) ;v85[v389]=v140[v142];break;end end end break;end end elseif ((v88>(85 -57)) or (4200==2332)) then local v222=0;local v223;while true do if (v222==(0 + (1189 -(442 + 747)))) then v223=v87[2 + 0 ];do return v85[v223](v13(v85,v223 + (1976 -(1913 + 62)) ,v87[3]));end break;end end else v85[v87[2 + (1135 -(832 + 303)) ]]=v85[v87[3]][v87[10 -6 ]];end elseif (v88<=30) then if (v85[v87[1935 -(565 + 1368) ]]==v85[v87[(961 -(88 + 858)) -11 ]]) then v79=v79 + (1662 -(1477 + 184)) ;else v79=v87[3 -0 ];end elseif (v88>(29 + 2)) then local v227=v87[2];local v228,v229=v78(v85[v227](v85[v227 + (857 -(564 + 292)) ]));v80=(v229 + v227) -1 ;local v230=0;for v344=v227,v80 do local v345=(0 + 0) -(0 + 0) ;while true do if ((v345==(0 -0)) or (1278>=1316)) then v230=v230 + (305 -(244 + 3 + 57)) ;v85[v344]=v228[v230];break;end end end else local v231=0;local v232;local v233;local v234;while true do if ((1082==1082) and (v231==(2 + 0))) then if (v233>(476 -(41 + 435))) then if (v234<=v85[v232 + (1002 -(938 + 63)) ]) then v79=v87[3 + 0 ];v85[v232 + (1128 -(936 + 189)) ]=v234;end elseif ((1328<=4878) and (v234>=v85[v232 + 1 + 0 ])) then local v488=1613 -(1565 + 48) ;while true do if (v488==(0 + 0)) then v79=v87[3];v85[v232 + (1141 -(782 + 356)) ]=v234;break;end end end break;end if (v231==(267 -(176 + 91))) then v232=v87[4 -2 ];v233=v85[v232 + (2 -0) ];v231=1093 -(975 + 117) ;end if (v231==(1876 -(157 + 1718))) then v234=v85[v232] + v233 ;v85[v232]=v234;v231=2 + 0 ;end end end elseif (v88<=(124 -89)) then if ((4087>=1355) and (v88<=(112 -79))) then local v143=v87[1020 -(697 + (1110 -(766 + 23))) ];local v144={};for v175=2 -1 , #v84 do local v176=(0 -0) -0 ;local v177;while true do if ((v176==(0 -0)) or (590>4650)) then v177=v84[v175];for v424=0 + 0 , #v177 do local v425=v177[v424];local v426=v425[1 -0 ];local v427=v425[5 -3 ];if (((v426==v85) and (v427>=v143)) or (3774<=3667)) then local v475=0;while true do if (v475==(1227 -(322 + 905))) then v144[v427]=v426[v427];v425[612 -(602 + 9) ]=v144;break;end end end end break;end end end elseif (v88>(1223 -((613 -164) + 740))) then local v235=v87[874 -(826 + 46) ];v85[v235](v13(v85,v235 + (948 -(245 + 702)) ,v80));else v85[v87[2]]={};end elseif ((1270<2146) and (v88<=(116 -79))) then if (v88==(12 + 24)) then if (v85[v87[1900 -(260 + 1638) ]]==v87[(1169 -725) -(382 + 58) ]) then v79=v79 + (3 -2) ;else v79=v87[3 + 0 ];end else v85[v87[(10 -7) -1 ]]=v85[v87[(1081 -(1036 + 37)) -5 ]][v87[1209 -(640 + 262 + 303) ]];end elseif (v88==38) then if (v85[v87[3 -1 ]]~=v85[v87[9 -5 ]]) then v79=v79 + 1 ;else v79=v87[1 + 2 ];end else local v239=1690 -(1121 + 569) ;local v240;local v241;local v242;local v243;while true do if ((4563>=56) and (v239==(216 -(22 + 192)))) then for v454=v240,v80 do local v455=0;while true do if (v455==(683 -(483 + 200))) then v243=v243 + 1 ;v85[v454]=v241[v243];break;end end end break;end if ((v239==(1464 -((2733 -1329) + 59))) or (446==622)) then v80=(v242 + v240) -(2 -(1 + 0)) ;v243=0;v239=2 -0 ;end if (v239==(765 -(468 + 297))) then v240=v87[(2044 -(641 + 839)) -(334 + (1141 -(910 + 3))) ];v241,v242=v78(v85[v240](v13(v85,v240 + (3 -2) ,v87[6 -3 ])));v239=1;end end end elseif (v88<=(83 -37)) then if ((2069>1009) and (v88<=42)) then if ((12<4208) and (v88<=(12 + 28))) then local v145=v87[238 -(141 + (242 -147)) ];v85[v145]=v85[v145](v13(v85,v145 + 1 + 0 ,v80));elseif ((v88>(105 -64)) or (2990<=2980)) then v61[v87[6 -3 ]]=v85[v87[1 + 1 ]];else local v246=v87[5 -3 ];v85[v246](v13(v85,v246 + 1 ,v80));end elseif (v88<=(31 + (1697 -(1466 + 218)))) then if (v88==(23 + 20)) then do return;end else v85[v87[(1 + 1) -0 ]]=v87[2 + 1 ]~=(163 -(92 + 71)) ;end elseif (v88>45) then v85[v87[1 + 1 ]]=v85[v87[4 -1 ]] -v87[769 -(574 + 191) ] ;else v85[v87[2 + 0 ]]=v85[v87[7 -4 ]]%v87[3 + 1 ] ;end elseif (v88<=(898 -(254 + 595))) then if ((v88<=(173 -(55 + 71))) or (2575>=4275)) then v85[v87[2 -0 ]]=v85[v87[1793 -(573 + 1217) ]] + v85[v87[4]] ;elseif (v88>((1280 -(556 + 592)) -84)) then if (v85[v87[1 + 1 ]]==v85[v87[5 -1 ]]) then v79=v79 + (940 -(714 + 225)) ;else v79=v87[8 -5 ];end else v85[v87[(1 + 1) -0 ]]=v85[v87[1 + (810 -(329 + 479)) ]]%v87[4] ;end elseif (v88<=(73 -22)) then if ((v88==(856 -(118 + 688))) or (3626<=1306)) then v85[v87[50 -(25 + 23) ]][v85[v87[857 -(174 + 680) ]]]=v85[v87[(3 -2) + 3 ]];else local v253=1886 -(927 + 959) ;local v254;while true do if ((1368<3780) and (v253==(0 -0))) then v254=v87[734 -((32 -16) + 716) ];do return v13(v85,v254,v254 + v87[5 -2 ] );end break;end end end elseif (v88==52) then v85[v87[(71 + 28) -((750 -(396 + 343)) + 86) ]]=v85[v87[6 -3 ]] + v87[289 -(175 + 110) ] ;elseif ( not v85[v87[4 -2 ]] or (3169==2273)) then v79=v79 + (4 -(1 + 2)) ;else v79=v87[1799 -(503 + 1293) ];end elseif ((2481<=3279) and (v88<=80)) then if (v88<=(184 -118)) then if (v88<=(43 + 16)) then if ((v88<=(1117 -(810 + 251))) or (1063<=877)) then if (v88<=(38 + 16)) then local v148=v87[1 + 1 ];local v149=v85[v87[3 + 0 ]];v85[v148 + (534 -(43 + 490)) ]=v149;v85[v148]=v149[v87[737 -(711 + 22) ]];elseif (v88>(212 -(1634 -(29 + 1448)))) then local v256=v87[861 -(240 + 619) ];v85[v256](v85[v256 + 1 + 0 ]);else do return;end end elseif (v88<=(89 -32)) then v85[v87[1 + 1 ]]=v85[v87[1747 -((2733 -(135 + 1254)) + 400) ]][v85[v87[4]]];elseif ((2314==2314) and (v88>(463 -(255 + 150)))) then v85[v87[2]][v87[(11 -8) + 0 ]]=v85[v87[3 + (4 -3) ]];else local v259=v87[8 -6 ];local v260=v87[12 -8 ];local v261=v259 + (1741 -(404 + 1335)) ;local v262={v85[v259](v85[v259 + (1 -0) ],v85[v261])};for v346=1 + 0 + 0 ,v260 do v85[v261 + v346 ]=v262[v346];end local v263=v262[1 + 0 ];if v263 then local v396=(1864 -(389 + 1138)) -(10 + 327) ;while true do if (v396==0) then v85[v261]=v263;v79=
