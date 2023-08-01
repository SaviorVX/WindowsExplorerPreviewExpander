# WindowsExplorerPreviewExpander
;reg setting for more text previews for almost every file, 
;in this case it allows explorer to view different extensions as text
;thus a quick preview is allowed. perfect for analysis for auick preview
;DLL Java Jar Python Etc

Windows Registry Editor Version 5.00

; .MACRO .SOUNDSCRIPT BPDX .BRF .XDP .XFD .ASL .ASP .BSDL .BSS .CA .CM .CFG .CPX .IEC .DLL .* .DLL .DOWNLOAD .PRR .EDML .EFM .EXP .PDB .- .GER .GNU .IEM .TSP .TS .INK .LNK .INUSE .ION .J .K .L .LNC .LO_ .MAR .MARKDOWN ;.NLC .NMBD .NOTES .NOW .NT .NWCTXT .OCR .PANIC PCL. .RFF .RIS .SKV .SMALI .SRX .SSA .TBD .TBL .TLX .TLX .TRT .TSV .TT .TTBL .TTE .TXT .VBS .VIS .VKP .VSP .VP .XML .XMP .MIB .MIT BBXT .BCR CHORD .CIF CONF .COO CPA .CPL ;.CPI CR .NIF DOC .EN .EXE FIL .FILE GO .INV HPM .HS .HTM HTML .HTML5 IGV .IGY LOG4 .LOG5 .- MD .MD5 .MK NIS .UEC .UCE PL .PLA .PLF PLIST .PLK PRI .WINMD PSD PSD1 SFB .SHA1 SPN .SPX .SRT TEXTCLIPPING THP .TLB .TLE U .V ;.W USG .UTF8 .$OL .001 .1 . .123 .21 .3 . .APPLICATION .APRJ.AQT .ARFF .BAD .BAS .BBS .BNA .BNX .BOG .CMD .CONF .DAT .CODE .COF .CON .CS .ASSEMBLY .DEA .DECTEST .DII .DEFINES .DSW .DSP .DE.FAQ .FFF .FFP .FULL .GBF .GEN ;.HHC .HHS .HLM .IDT .IDX .IEM.KLG .KOR .LA.LABEL . .LNG .EMULE ..MANIFEST .MARKDOWN . .MP3 .MPL .MYDOCS .NFO .NCLK .NEW .NFO .OEM1 .OEM2 . .PD .PDU .PFS.PGW .PHR .PJS .STRINGS .SUB .TNEF .TPH .TRN .TXK .TXT .U3 . .UHTML ;.UK .US .USER .USF .VFK .VHD .VHDL .X70 .X8V0 .XFF .XLF .XLOG .ZIB .ZW .ZXE .$01 .$05 .$O1 DISKDEFINES .1ST .7 .82T .4 .5 .SO .8BIT .JRS .P7X . ._ME .ABT .AC .ADIUM .ADIUMLOG .ADW .ALX .AML .ANDROID . .AWA .AWB .AWH ;.AXT .BA1 .BAK .BAT .BIN .BLM .BLN .BLW. .DCE .DDD .DEV .DSML .DTD .ECSV .F .G .H .I .FNX .FPT .FR .FRA .FRM .FSA..HZ .ID31 .IDC .KAR .KCH .KIX .LXFML .LYR .LYT .MTXT .MW .NBR .PANIC .PC5 .PCC .README .REG .SDNF .SEN ;.SEQ .SHA1 .SYS .TEXT .TX8 .TX .TXA .TXD .TXE .TXH. .WTX .X20 .X60.YML .ZED .ZHP .3D 5 .6 .89T .92T .9XT..BIG .BIG5 .BK .CHK .SKR .ANI .DAT .DBT .DCD .DESC .DFE .DFM .DOF .DP .DPV . .DQY .DRP .DSC .EMU .FR .UK .INI .- ;.A .JSON .LNK .MAK .LUE .LUF .LWD. .MARKUP .MATHML . .MDLE .MDOWN .OPC .OPENBSD .OSN .P3X .PAC .PSB .PT3 .PVJ. .PSM1 .PY .REG.QUD .RDF .REA .USF .OEM4 .OEM .VCF .VER .VERS .WKF .WN .WRD . .WRL .WSH .WST .XSR .XWP .XY ;.XYP .XYW .XYZ .XYZ .XZ .CFG .Q .R .S .T . .ADL .ADOC .ADT.BEA .BEL .BEP .CA .CM .GO .CLIP .CLIPPING .COM .RS .RSP .CTX .CURL . .DOK .PAS .DRP .ENF .ERR .ES .ETF .ETX .GTX .GUIDE .HDR.IT .JA .JAM .JSS .JTX .KAHL . ;.LINUX .LINX .LISP .LOG1 .LOG2 .LOG3 . .LTR .LTT .LTX .M .N .O .P.MKD .MKDN .MODD.PRC .PRN .PROJECT .READ .README .LIB .RU .RUS .RZN .S19 .S2K .S2S .SAMI .SBV.SEP .CONFIG .SDI .SNW .SOAP .SCRIPT .TDUMP .TED .TEXT .BLF ;.AX .MOF .DOWNLOAD .IIF .ILL .INC."$00 .$02 .$04. .EMULECOLLECTION .ING. .EUC .EXT .EXTRA. .LANGUAGE .LAS .PVW .Q&A .QDT .TM .TMPRTF .TMX .VSMPROJ .VSMPROJ .ANNOT .ANS .ANSI .ARTASK .ASC .ASCII ASS .ASSOC .ATT .B .C .D ;.E. BDN .BDP .BDR BT .CAG .CAS .CAT .PNF .DB .CC .CD2 .CDT .CHARSET .SET .CHO .CIL .CKN .CLG CLIX .CM0013 .COLLECT .COLLECTION .CRASH .CRD .CRWL.CRDOWNLOAD .OLD .CSASSEMBLY .CSV .CTD .CTF .CTL DB3 .32 .64 .DEC .TEST ;.DES .DESKTOP .DOCUMENT .DKZ .DMR .DNE DOC .DIZ .DK .DRV .NLS .MSC EIA .FIN .FIRST .FLR. GPL .GTHR HTMLS .HTX .HVC .INF .ACM .LOG IPR .ISI .ISR JAR .JAV .JAVA .JEB .JIS .JP1 JFM .PDF .FILE .LAY .LDF .LIN LINK .SHORTCUT. ;LOG .LRC .LST LUE .NORTON .MAN .MANIFEST .MAP MAXFR .MCW .MD .MDTEXT .MDTXT .MDWN .MEZ .MF MPSUB .MSS .MTX. NNA .NOKOGIRI .NOT OBJ .OCX .PS .ODC .OH .OJP .OEM3 .OEM5 .OMN .OOGL .OOT .OPML .ORT .OSI .PLN .PMO .POD PS1 ;.PS1XML .PSC1 . REGTRANS .MS . REGTRANS-MS .REG . REPORT .RESP .REST RML .RST .RT .RTF .RTL .RTX RUST .EN .ENC SCCD .CHM .RTF .SHA512 .SK .SKCARD SMF .SMI .SMS SOURCE .SPEC .SPG .SSF .ST1 .STRING .SYN .T2T TAB TCE .TCM ;.TDF TEXTILE .TFW .TGF .TTF .TTPL .TTXT. UNAUTH .UNI .UNX .UTX .UTXT .V2T .VBX .XAML .XML .VMG .VNA .VTT .VW .VW3 . VXML .VZM .WER .X64 .X32 .X86 X90VW3 .XC0 .XDL .XSD .XSL .XSLT .Y .Z .2 .3.


[HKEY_CLASSES_ROOT\.ink]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.lnk]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.link]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.shortcut]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.A]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.B]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.C]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.D]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.E]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.F]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.G]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.H]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.I]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.J]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.K]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.L]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.M]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.N]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.O]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.P]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.Q]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.R]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.S]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.T]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.U]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.V]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.W]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.Y]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.Z]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.DEV]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.DSW]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.DSP]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.NEW]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.2]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.3]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.4]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.5]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.so]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.cat]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.pnf]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.db]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.db3]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.32]
"PerceivedType"="text"



[HKEY_CLASSES_ROOT\.64]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.x64]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.x32]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.x86]
"PerceivedType"="text"



[HKEY_CLASSES_ROOT\.READ]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.README]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.LIB]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.EXP]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.PDB]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.-]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.CR]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.NIF]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.DOWNLOAD]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.crdownload]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.OLD]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.JFM]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.PDF]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\FILE]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.USF]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\OEM4]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\OEM]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\OEM1]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\OEM2]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\OEM3]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\OEM5]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.regtrans-ms]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.reg]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.regtrans]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ms]
"PerceivedType"="text"




[HKEY_CLASSES_ROOT\.blf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.AX]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mof]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cpa]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.CPL]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.CPi]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cpx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.iec]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.drv]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.nls]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.msc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.com]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rs]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rsp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sep]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.config]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sdi]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.nis]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.uec]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.uce]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.iem]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tsp]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.ts]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vsp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.inf]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.acm]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\LOG]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\LOG1]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\LOG2]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\LOG3]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\LOG4]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\LOG5]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.!!!]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.$00]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.$02]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.$04]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.$01]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.$05]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.$o1]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.$ol]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.001]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.1]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.1st]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.7]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.82t]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.89t]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.92t]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.9xt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\._me]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.abt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ac]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.adium]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.adiumlog]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.adl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.adoc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.adt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.adw]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.alx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.aml]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.android]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.annot]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ans]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ansi]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.application]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.aprj]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.aqt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.arff]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.artask]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.asc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ascii]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.asl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.asp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ass]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.assoc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.att]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.awa]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.awb]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.awh]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.axt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ba1]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bad]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bas]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bbs]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bbxt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bcr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bdn]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bdp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bdr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bea]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bel]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bep]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.big]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.big5]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bk]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.blm]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bln]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.blw]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bna]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bnx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bog]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bpdx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.brf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bsdl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bss]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cag]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cas]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cd2]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cdt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.charset]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.SET]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.cho]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.chord]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cif]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cil]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ckn]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.clg]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.CLIP]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.clipping]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.clix]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cm0013]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.code]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cof]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.con]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ca]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cm]
"PerceivedType"="text"



[HKEY_CLASSES_ROOT\.cfg]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.conf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.coo]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.crash]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.crd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.crwl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.CS]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ASSEMBLY]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.csassembly]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.csv]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ctd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ctf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ctl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ctx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.curl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dat]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dbt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dcd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dce]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ddd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.de]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dea]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dectest]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dec]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.test]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.des]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.desc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dfe]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dfm]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dii]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.defines]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.diskdefines]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.DOC]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.diz]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dk]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dkz]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dmr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dne]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dok]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.Pas]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.DRP]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.DOF]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dpv]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dqy]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.drp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dsc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dsml]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dtd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ecsv]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.edml]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.efm]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.eia]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.emulecollection]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ING]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.LNG]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.EMULE]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.COLLECT]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.COLLECTION]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.EMU]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.fr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.uk]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ca]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cm]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.go]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rust]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.en]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.enc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.enf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.err]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.es]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.etf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.etx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.euc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ext]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.extra]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.faq]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.fff]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ffp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.fil]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.file]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.fin]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.first]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.flr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.fnx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.fpt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.fr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.fra]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.frm]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.fsa]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.full]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.gbf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.gen]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ger]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.gnu]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.gpl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.gthr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.gtx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.guide]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.hdr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.hhc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.hhs]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.hlm]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.hpm]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.hs]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.htm]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.html]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.html5]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.htmls]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.htx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.hvc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.hz]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.id31]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.idc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.idt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.idx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.iem]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.igv]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.igy]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.iif]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ill]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.inc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.inuse]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ion]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ipr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.isi]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.isr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.it]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ja]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.jam]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.jeb]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.jis]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.jp1]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.jss]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.jtx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.kahl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.kar]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.kch]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.kix]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.klg]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.kor]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.la]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.label]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.language]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.las]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.lay]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ldf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.lin]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.linux]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.linx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.lisp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.lnc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.lo_]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.log]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.lrc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.lst]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ltr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ltt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ltx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.lue]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.luf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.lwd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.lxfml]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.lyr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.lyt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.macro]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.man]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.manifest]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.map]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mar]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.markdown]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.Markdown]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.markup]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mathml]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.maxfr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mcw]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.md]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mdle]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mdown]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mdtext]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mdtxt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mdwn]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mez]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mib]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mit]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mkd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mkdn]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.modd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mp3]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mpl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mpsub]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mss]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mtx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mtxt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mw]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.nbr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.nclk]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.new]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.nfo]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.nlc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.nmbd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.nna]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.nokogiri]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.not]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.notes]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.now]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.nt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.nwctxt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ocr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.odc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.oh]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ojp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.omn]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.oogl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.oot]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.opc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.openbsd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.opml]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ort]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.osi]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.osn]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.p3x]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pac]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.panic]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pc5]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pcc
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.panic]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pcl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pdu]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pfs]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pgw]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.phr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pjs]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pla]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.plf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.plist]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.plk]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pln]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pmo]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pod]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.prc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.prn]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.project]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.DOWNLOAD]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.prr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.psb]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pt3]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pvj]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pvw]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.q&a]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.qdt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.qud]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rdf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rea]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.readme]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.reg]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.report]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.resp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rest]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rff]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ris]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rml]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rst]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rtf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rtl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rtx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ru]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rus]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.rzn]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.s19]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.s2k]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.s2s]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sami]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sbv]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sdnf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sen]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.seq]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sfb]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sha1]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sha512]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sk]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.skcard]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.skv]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.smali]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.smf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.smi]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sms]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.snw]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.soap]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.script]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.soundscript]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.source]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.spec]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.spg]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.spn]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.spx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.srt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.srx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ssa]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ssf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.st1]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.STRING]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.strings]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sub]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.DESKTOP]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.DOCUMENT]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.syn]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.t2t]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tab]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tbd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tbl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tce]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tcm]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tdf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tdump]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ted]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.text]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.textclipping]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.textile]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tfw]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tgf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.thp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tlb]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tle]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tlx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tlx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.LUE]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.Norton]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tm]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tmprtf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tmx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tnef]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tph]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.trn]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.trt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tsv]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ttbl]

"PerceivedType"="text"
[HKEY_CLASSES_ROOT\.tte]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ttf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ttpl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ttxt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tx8]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.tx?]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.txa]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.txd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.txe]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.txh]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.txk]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.txt]


[HKEY_CLASSES_ROOT\.u3]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.uhtml]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.uk]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.unauth]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.uni]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.unx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.us]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.user]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.usf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.usg]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.utf8]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.utx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.utxt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.v2t]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vcf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ver]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vers]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vfk]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vhd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vhdl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vis]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vkp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vmg]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vna]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vsmproj]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vsmproj]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vtt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vw]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vw3]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vxml]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vzm]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.wer]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.wkf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.wn]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.wrd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.wrl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.wsh]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.wst]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.wtx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.x20]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.x60]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.x70]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.x8v0]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.x90vw3]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xc0]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xdl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xdp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xfd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xff]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xlf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xlog]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xml]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xmp]

[HKEY_CLASSES_ROOT\.xsd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xsl]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xslt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xsr]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xwp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xy]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xyp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xyw]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xyz]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.yml]

[HKEY_CLASSES_ROOT\.zed]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.zhp]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.zib]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.zw]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.zxe]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.123]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.21]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.3]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.3D]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.5]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.6]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.8bit]
"PerceivedType"="text"


[HKEY_CLASSES_ROOT\.JRS]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.P7x]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.pRi]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.WinMD]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.SCCD]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.CHM]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.RTF]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.CHK]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.SkR]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ani]
@="anifile"
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.BAK]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bat]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.bin]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cmd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.conf]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.dat]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.DLL]
@="Dynamic Link Libary (*.DLL)"
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.doc]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.en]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.exe]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.Go]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.inv]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.jar]
@="WinRAR"
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.jav]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.java]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.json]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.lnk]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mak]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.manifest]
"PerceivedType"="text"
"PercievedType #Backup"="System"

[HKEY_CLASSES_ROOT\.markdown]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.MD]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.md5]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mk]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.mydocs]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.nfo]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.obj]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ocx]
"PerceivedType #Backup"="system"
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ps]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ps1]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ps1xml]
"PerceivedType"="Text"

[HKEY_CLASSES_ROOT\.psc1]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.psd]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.psd1]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.psm1]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.Py]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.reg]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sha1]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.sys]
@="sysfile"
"PerceivedType #Backup"="system"
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.text]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.txt]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vbs]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.vbx]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xaml]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xml]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xyz]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.xz]
@="WinRAR"
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.cfg]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.ini]
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.]
"PerceivedType"="text"
