# Lab #2   

This lab covered a list of common prompts used in the terminal:

* hostname
```
PS C:\Users\jrichar7> hostname
Jernique
```
---

* env
```
PS C:\Users\jrichar7> env
ALLUSERSPROFILE=C:\ProgramData
APPDATA=C:\Users\jrichar7\AppData\Roaming
COMMONPROGRAMFILES=C:\Program Files\Common Files
CommonProgramFiles(x86)=C:\Program Files (x86)\Common Files
CommonProgramW6432=C:\Program Files\Common Files
COMPUTERNAME=JERNIQUE
COMSPEC=C:\Windows\system32\cmd.exe
DriverData=C:\Windows\System32\Drivers\DriverData
HOMEDRIVE=C:
HOMEPATH=\Users\jrichar7
IGCCSVC_DB=AQAAANCMnd8BFdERjHoAwE/Cl+sBAAAAcynqUrJlGEmB0jMyOs6KQwQAAAACAAAAAAAQZgAAAAEAACAAAAAAR0++CY34sEUCwCb8Z31mjAIXEcc8Z/65Nb/6daxIrQAAAAAOgAAAAAIAACAAAADoAWVDUcWMFCiLkzjbbbrfZ2SVtgONK9dhSdL7TuW9NGAAAABNSIUcm6c51nzNUaR9//LZDZVInBGfZFCYwTSCKm6YqTXetUnzTwrdTCsWPdwevWvKLZALKYEw44a4unciM5Mj4o+ObEVGXnC4ME/w4PjQbOkaxishlgTFQ2g2qp9ohGBAAAAAboEJ1nXzlVaQCIBSi822YZ7r9pme9lDGdUDC6trZKba7+J9iIPreGZespzB2V1X3L0J0XZ7lE8QVMwnRkBD8lA==
LOCALAPPDATA=C:\Users\jrichar7\AppData\Local
LOGONSERVER=\\JERNIQUE
NUMBER_OF_PROCESSORS=12
OneDrive=C:\Users\jrichar7\OneDrive - stevens.edu
OneDriveCommercial=C:\Users\jrichar7\OneDrive - stevens.edu
OS=Windows_NT
PATH=/c/Program Files (x86)/NVIDIA Corporation/PhysX/Common:/c/Windows/system32:/c/Windows:/c/Windows/System32/Wbem:/c/Windows/System32/WindowsPowerShell/v1.0:/c/Windows/System32/OpenSSH:/c/Program Files/dotnet:/c/Program Files/Microsoft SQL Server/Client SDK/ODBC/110/Tools/Binn:/c/Program Files (x86)/Microsoft SQL Server/120/Tools/Binn:/c/Program Files/Microsoft SQL Server/120/Tools/Binn:/c/Program Files/Microsoft SQL Server/120/DTS/Binn:/c/Program Files (x86)/Windows Kits/8.1/Windows Performance Toolkit:/c/Program Files/nodejs:/c/Program Files (x86)/Git/cmd:/c/Program Files/MATLAB/R2023a/bin:/c/Users/jrichar7/Downloads/ghdl-UCRT64/GHDL/bin:/c/Users/jrichar7/Downloads/gtkwave-3.3.100-bin-win64/gtkwave64/bin:/c/Users/jrichar7/AppData/Local/Programs/Python/Python311/Scripts:/c/Users/jrichar7/AppData/Local/Programs/Python/Python311:/mingw64/bin:/usr/bin:/c/Users/jrichar7/AppData/Local/Microsoft/WindowsApps:/c/Users/jrichar7/AppData/Local/Programs/Microsoft VS Code/bin:/c/Users/jrichar7/AppData/Roaming/npm
PATHEXT=.COM;.EXE;.BAT;.CMD;.VBS;.VBE;.JS;.JSE;.WSF;.WSH;.MSC;.CPL
PROCESSOR_ARCHITECTURE=AMD64
PROCESSOR_IDENTIFIER=Intel64 Family 6 Model 141 Stepping 1, GenuineIntel
PROCESSOR_LEVEL=6
PROCESSOR_REVISION=8d01
ProgramData=C:\ProgramData
PROGRAMFILES=C:\Program Files
ProgramFiles(x86)=C:\Program Files (x86)
ProgramW6432=C:\Program Files
PSModulePath=C:\Users\jrichar7\OneDrive - stevens.edu\Documents\WindowsPowerShell\Modules;C:\Program Files\WindowsPowerShell\Modules;C:\Windows\system32\WindowsPowerShell\v1.0\Modules;C:\Program Files (x86)\Microsoft SQL Server\120\Tools\PowerShell\Modules\
PUBLIC=C:\Users\Public
SESSIONNAME=Console
SW_SIM_HYDRA=C:\Program Files\Common Files\SolidWorks Shared\Simulation Worker Agent\
SW_SIM_MPIT=INTELMPI
SW_SIM_TEMP=C:\ProgramData\SOLIDWORKS\SW_net_sim_temp\
SYSTEMDRIVE=C:
SYSTEMROOT=C:\Windows
TEMP=/c/Users/jrichar7/AppData/Local/Temp
TMP=/c/Users/jrichar7/AppData/Local/Temp
USERDNSDOMAIN=campus.stevens-tech.edu
USERDOMAIN=CAMPUS
USERDOMAIN_ROAMINGPROFILE=CAMPUS
USERNAME=jrichar7
USERPROFILE=C:\Users\jrichar7
WINDIR=C:\Windows
WSLENV=WT_SESSION:WT_PROFILE_ID:
WT_PROFILE_ID={61c54bbd-c2c6-5271-96e7-009a87ff44bf}
WT_SESSION=d563df26-5af3-4f61-87a0-6b47f5b5bf42
ZES_ENABLE_SYSMAN=1
TERM=xterm-256color
HOME=/home/jrichar7
```

---

* ps
```
PS C:\Users\jrichar7> ps

Handles  NPM(K)    PM(K)      WS(K)     CPU(s)     Id  SI ProcessName
-------  ------    -----      -----     ------     --  -- -----------
    171      10     2568       7796              4856   0 AdminService
    141       9     2572       8524              9012   0 AggregatorHost
    223      19    50684      17956      12.50  11040   1 ai
    223      18    22784      18856       0.13  19748   1 ai
    223      18    26416      18904       0.19  21820   1 ai
   1144      47    64648      43744       3.02  11740   1 ApplicationFrameHost
    385      25    30384      52656       3.00   2272   1 chrome
    422      36   103336     101392      17.45   2624   1 chrome
    278      25    75140     100196       0.23   2712   1 chrome
    369      27    93712     145768       1.41   3540   1 chrome
    263      17     9072      19872       7.08   4428   1 chrome
    369      27    92564     141252       2.16   5760   1 chrome
    428      31   126896     178440      12.81   5996   1 chrome
    317      24    58740      82496      82.42   7492   1 chrome
    395      29    72572     121304       9.14   8928   1 chrome
    373      28    89016     140132       1.17   9260   1 chrome
    574      27    49672      34384       1.13   9628   1 chrome
    301      25    56376      66876       1.52  10760   1 chrome
    254      18    17148      21168       9.00  11096   1 chrome
    294      21    17504      35144       0.56  11276   1 chrome
    344      24    30720      67384       1.45  11480   1 chrome
   3262      81  1160012     655956     539.42  11664   1 chrome
   6074     115   287424     360608     955.84  12640   1 chrome
    329      26    45348      74720       4.02  12912   1 chrome
    555      50   247212     273936      14.19  13300   1 chrome
    548      45    99556      77280     130.30  13380   1 chrome
    406      11     2272       7524       0.38  14044   1 chrome
    330      23    26376      50108       3.14  15140   1 chrome
    604      43   211820     223060      28.78  16292   1 chrome
    284      26    50248      77364       0.67  18860   1 chrome
    361      29    95344     146984       1.17  19404   1 chrome
    458      38   116412     105680      10.00  20368   1 chrome
    376      28    84208     147360       1.58  20588   1 chrome
    373      27    92136     140604       0.84  21808   1 chrome
    377      30   103328     154264       1.59  23060   1 chrome
    464      43   275428     130120     113.14  24572   1 chrome
    624      47   236040     251964       8.72  24820   1 chrome
    380      27    60392      82160       3.63  24836   1 chrome
    432      33   117428     160276      29.97  26304   1 chrome
    378      29    61116      70944       2.70  27276   1 chrome
    390      30    81108      85320       6.88  27336   1 chrome
    397      31    86640      85384       3.19  27404   1 chrome
    358      29    35628      95748       0.09  28296   1 chrome
    365      27    83504     126248       1.77  31324   1 chrome
    391      35   158476      99296      10.78  32228   1 chrome
    413      35   107756     161148       4.80  32856   1 chrome
    239      19    17364      29556       0.00  32980   1 chrome
    368      24    34820      62336       0.44  34416   1 chrome
     88       6     2280       4944       0.00   3992   1 cmd
     98       8     2372       5468       0.00  13112   1 cmd
     88       6     2276       5068       0.02  13700   1 cmd
    160      11     5800       8156              3580   0 conhost
    161      11     5804       8044              5724   0 conhost
    160      11     5816       7988              6660   0 conhost
    117       8     5384       5856              7188   1 conhost
    160      11     5792       8056              8912   0 conhost
    160      11     5784       8056             12152   0 conhost
    160      11     5808       8052             14292   0 conhost
    160      11     5792       8044             16572   0 conhost
    161      11     5792       8052             18340   0 conhost
    145       9     1392       8472       0.00  22916   1 conhost
   1014      37     3436       6716               896   1 csrss
   1005      35     2352       5356              1004   0 csrss
    757      22    12288      29652      40.84  13836   1 ctfmon
    433      19     7848      15708              5512   0 dasHost
    128       9     1836       7484             23848   0 dasHost
    264      14     5332      22864       0.05  30236   1 DataExchangeHost
    186      10     2024       7920             22440   0 DDVCollectorSvcApi
    773      94    82524      54876             12708   0 DDVDataCollector
    310      20    18672      13316              5508   0 DDVRulesProcessor
    825      62    39160      58620             11384   0 Dell.CoreServices.Client
   1615     129   127852      71040             19204   0 Dell.D3.WinSvc
    688      47    59028      50696             19348   0 Dell.DCF.UA.Bradbury.API.SubAgent
    706      61    47452      30672              4872   0 Dell.TechHub
    821      91    72268      55276             11876   0 Dell.TechHub.Analytics.SubAgent
    708      76    78328      74816             19320   0 Dell.TechHub.DataManager.SubAgent
    729      84    50136      38988             19308   0 Dell.TechHub.Diagnostics.SubAgent
   1474     142   144020     145208             11420   0 Dell.TechHub.Instrumentation.SubAgent
    729      79    53264      53804             19796   1 Dell.TechHub.Instrumentation.UserProcess
   1284      86    70444      72092              4736   0 DellOptimizer
    200      12    14932      20164       0.11   1712   1 Discord
   1518      33   221332      84496       6.28   2708   1 Discord
    275      16    16100      52756       1.38   4940   1 Discord
   1164      79   276520     267764   2,330.47   6372   1 Discord
    334      19    20100      37936       6.63  16036   1 Discord
   1020      57   117204      81484     146.55  16596   1 Discord
    124      11    18020       5908              6500   0 dispatcher
    893      48    14492      23464       1.55  13020   1 dllhost
    182      10     2984      11992       0.31  16604   1 dllhost
    270      15     4192      11628             20604   0 dllhost
    135       9     1720       8404       0.09  27376   1 dllhost
    108       9     1664       5796      77.88  10184   1 dptf_helper
   3342     142   427832     203576              2784   1 dwm
    226      12     4244      10144      59.92   1660   1 ECDBWM
    437      16     9980      17972             20080   0 ECDBWM
    258      14    14424      14444              9588   0 ECDBWMService
    147       9     2068       6552              5028   0 esif_uf
    134      10     1508       6268              4992   0 EwServer
  10291     222   494948     407272     174.59  10904   1 explorer
    384      16    27936      23716              4240   0 ExpressConnect
    593      24   142052      52232              9752   0 ExpressConnectNetworkService
    258      14    14436      14452              2300   0 ExpressConnectService
    244      16     5496      19284       0.64  20188   1 FileCoAuth
    202      15     2892      10036              5060   0 FNPLicensingService
    185      12     2472       8868              5076   0 FNPLicensingService64
     42       8     4604       3704              1344   0 fontdrvhost
     42      10     8016       7172              1352   1 fontdrvhost
    281      32    12996      34188       0.92  12560   1 gtkwave
    815      80    42760      74424       2.70  30468   1 gtkwave
    303      14     4560      11580              4732   0 HPPrintScanDoctorService
   1403      56   172628      94892       6.44  12984   1 HxOutlook
    767      32    33684      38496       6.11   6204   1 HxTsr
      0       0       60          8                 0   0 Idle
    199      11     2288       8692              2504   0 igfxCUIServiceN
    421      15     4248      12524       1.08   6824   1 igfxEMN
    395      36    40016      22668              5132   0 IntelAudioService
    149       8     1380       5220              2000   0 IntelCpHDCPSvc
    147       9     1384       6272              5148   0 jhi_service
    226      12     3140      10164              5268   0 LMS
    199      12     2288       6884       0.77   3824   1 LocationNotificationWindows
    899      39    50720      74080       6.91  15364   1 LockApp
     65      11     1376       3652              1100   0 LsaIso
   2630      38    17916      32912              1116   0 lsass
    183      14     2360       6708              4864   0 mDNSResponder
      0       0     4164    1173848              3160   0 Memory Compression
   1461      80    91964      98212       5.92  11852   1 Microsoft.Notes
    581      34    94328      53864      11.42  16764   1 Microsoft.SharePoint
    489      21    27800      27232             21756   0 MoUsoCoreWorker
    504      19    11772      19604              5284   0 MpDefenderCoreService
    242      14     3272       8540             16556   0 msdtc
    331      24    54400      89672       0.80   2444   1 msedge
    343      24    16924      43396       0.31   7064   1 msedge
   1653      64    77844     171756       1.16  11208   1 msedge
    179      12     8784      19684       0.06  21680   1 msedge
    210      17    14272      28100       0.00  24356   1 msedge
    321      20    22012      53948       0.03  25040   1 msedge
    192      11     2240       8608       0.00  25484   1 msedge
    245      15     8120      23184       0.03  26676   1 msedge
    488      29    79840      74928       0.17  27076   1 msedge
    203      14     7212      18020       0.03  30276   1 msedge
    479      28    80176     122576       0.98  34452   1 msedge
    218      14     7540         16       1.22   4424   1 msedgewebview2
    180      12     9088         16       1.42   6972   1 msedgewebview2
    169      10     2236       7316       0.08   7288   1 msedgewebview2
   1404      53    47472       7652      23.69   8276   1 msedgewebview2
    367      22    12528      19616       0.66   8752   1 msedgewebview2
   1166     147   354416       8996     125.66   9712   1 msedgewebview2
    154      10     2192       7712       0.03  14644   1 msedgewebview2
    381      22    15316       1632       6.45  21448   1 msedgewebview2
   1613      36   226560       5560      25.30  21464   1 msedgewebview2
   1257      51    38424      44628       3.41  29420   1 msedgewebview2
    497      27    71484       9440       0.34  30540   1 msedgewebview2
    340      37   175752      42300       3.97  31304   1 msedgewebview2
    172      11     8224       6008       0.08  34652   1 msedgewebview2
   1132     236   394192     229364              6156   0 MsMpEng
    814      45    23000      22920       2.61  28720   1 msteams
    218      12     4176      10060              7296   0 NisSrv
    878      37    66296      81376       1.34   6080   1 Notepad
    206      13     2908      13180       0.02   6688   1 Notepad
    366      19     7732      18792              2844   0 NVDisplay.Container
    756      33    59628      55076              3760   1 NVDisplay.Container
    168      10     3528       8400              5552   0 nvWmi64
    221      14     6392      13140             11104   1 nvWmi64
    880      28    48780      38112              4948   0 OfficeClickToRun
    670      23    34684      25708              3416   0 OneApp.IGCC.WinService
   4583      95   318716     261320     364.80   3124   1 ONENOTE
    269      15     3580       2704       0.05  16756   1 ONENOTEM
    170      11     2340      10096       0.00   1532   1 OpenConsole
    168      11     2352      10044       0.00  16832   1 OpenConsole
    168      11     2336       9676       0.02  18948   1 OpenConsole
    223      13     2676      11240       0.02  31736   1 OpenConsole
    561      33    13736      63572       0.08  13404   1 OpenWith
    325      21     5312      16420       3.39  16084   1 PanGPA
    381      24    10016      15280              5560   0 PanGPS
    990      55   103236     131096       0.06   7644   1 Photos
   2083     101   157972     213584       4.28  10932   1 Photos
   2659      79   246288     212776      25.19   4064   1 POWERPNT
    570      28    55872      68112       0.31  34072   1 powershell
    140       8     1460       5856              5596   0 QcomWlanSrvx64
      0      39    15512      49880               196   0 Registry
    128       8     1400       5568              5576   0 remotesolverdispatcherservice
    167      11     2028       7276              5604   0 RstMwService
    495      16     5388      12608              5620   0 RtkAudUService64
    443      16     4960      14748             12500   1 RtkAudUService64
    426      15     5996      13492       0.59  15600   1 RtkAudUService64
    422      25     9092      33268       1.77  12048   1 RuntimeBroker
    846      39    18144      58664       6.55  12140   1 RuntimeBroker
    339      17     7684      21752       0.44  12264   1 RuntimeBroker
    730      30     9840      42832       2.58  15404   1 RuntimeBroker
    569      27    15388      37336      16.23  15696   1 RuntimeBroker
    170      11     2368      11084       0.14  24296   1 RuntimeBroker
    272      15     6080      22344       0.00  30400   1 RuntimeBroker
    455      21     6584      30032       1.48  33840   1 RuntimeBroker
    160      10     2200      10468       0.00  34588   1 RuntimeBroker
   1919     224   350460     131936      32.23  11784   1 SearchHost
    837      30    48272      45828             12540   0 SearchIndexer
      0       0      188      42016               140   0 Secure System
    497      22     8016      18160              6636   0 SecurityHealthService
    193      11     2116       9292       0.11  15424   1 SecurityHealthSystray
   1117      20     8464      12892              1056   0 services
   3166      65   131808      84604             14880   0 ServiceShell
   1577      64    99380     109636       5.91  17312   1 ShellExperienceHost
    897      23     9352      40484      33.84   7072   1 sihost
    370      20    20644      20864     952.72  19072   1 sldBgDwld
    221      31    26932      58088       0.11  15848   1 sldworks_fs
    185      11     2708      10896       0.00  29348   1 smartscreen
     58       4     1140       1108               640   0 smss
    618      36    56308      97928       0.13  15452   1 SnippingTool
    628      32    11156      20964              4508   0 spoolsv
    134      12     1548       4960              5676   0 sqlbrowser
    601     177   343844      57432              5328   0 sqlservr
    155      11     1908       7268              5664   0 sqlwriter
   1122      50   117252     109300      12.56  11808   1 StartMenuExperienceHost
   1231     215   258460     117724             20308   0 SupportAssistAgent
    249      12     3316       7452              1052   0 svchost
    226      16     2076       6676              1068   0 svchost
    132      11     1640       5288              1136   0 svchost
   1877      32    20192      38488              1308   0 svchost
   1986      34    18528      22832              1484   0 svchost
    351      14     3480       8104              1544   0 svchost
    468      10     2960       7188              1596   0 svchost
    110      11     1248       4996              1668   0 svchost
    333      17     3876      11248              1676   0 svchost
    194      48     9404       9200              1700   0 svchost
    348      16     3752      13832              1740   0 svchost
    466      15     3208       9956              1820   0 svchost
    261      14     3228       9340              1840   0 svchost
    314      10     2124       9408              1848   0 svchost
   1203      26    11100      17656              1880   0 svchost
    588      14     3528       8748              2020   0 svchost
    266      14     2840       8368              2140   0 svchost
    359      18     4060       8680              2316   0 svchost
    197      14     2020       7892              2324   0 svchost
    153       9     1804       7344              2360   0 svchost
    207      10     2104       7120              2364   0 svchost
    429      27    22944      23544              2388   0 svchost
    311       8     1352       5412              2404   0 svchost
    290      14     4552      14384              2428   0 svchost
    244      18     3384      12368              2480   0 svchost
    198      11     2388       9328              2492   0 svchost
    304      13     3716       9392              2880   0 svchost
    515      15    20236      17740              3032   0 svchost
    422      19     6560      14284              3060   0 svchost
    155      10     1800       8136              3092   0 svchost
    243      12     2524       9104              3132   0 svchost
    305       8     2276       6228              3140   0 svchost
    218      13     2452      13876              3148   0 svchost
    320      14     4064      13652              3232   0 svchost
    169      10     1540       6384              3396   0 svchost
    127       8     1332       5836              3520   0 svchost
    398      14     3064      12408              3704   0 svchost
    576      21    13136      21704              3788   0 svchost
    363      15    26500      29708              4048   0 svchost
    534      16     7896      16640              4080   0 svchost
    224      12     2604       9856              4260   0 svchost
    598      31    13868      23296              4376   0 svchost
    265      16     3456      12208              4416   0 svchost
    460      35    14424      15936              4544   0 svchost
    194      12     1972       7024              4588   0 svchost
    270      15     2740       7352              4832   0 svchost
    139       9     1560       6788              4836   0 svchost
    208      13     3224      14452              4844   0 svchost
    302      14     3320      11792              4880   0 svchost
    794      36    30952      44128              4892   0 svchost
    342      31     4876      14576              4912   0 svchost
    395      28    39660      44960              4920   0 svchost
    139      10     1608       6432              5000   0 svchost
    375      21     3012      10064              5140   0 svchost
    215      13     2516       9008              5296   0 svchost
    313      15     3132       9700              5712   0 svchost
    206      16     7084       8992              5764   0 svchost
    284      12     2892       8056              5816   0 svchost
    136       8     1552       5544              5848   0 svchost
    168      11     3616      11196              5948   0 svchost
    272      16     2908       8492              6016   0 svchost
    460      22     5844      21476              6116   0 svchost
    141       9     1424       6056              7084   0 svchost
    167      11     1720       6788              7260   0 svchost
    198      12     1712       7132              8680   0 svchost
    406      22     8432      24688              8692   0 svchost
    356      20     4860      21340              8796   0 svchost
    483      20     8220      28288       4.92   8956   1 svchost
    635      39    13160      22060              9148   0 svchost
    155      10     2128       8512       0.08  10256   1 svchost
    764      30    13324      46928      21.53  10296   1 svchost
    536      30    11800      24616             10352   0 svchost
    257      15     3928      11316             10400   0 svchost
    415      22     5760      18572             11184   0 svchost
    423      19     7020      29924       2.31  11400   1 svchost
    486      26     5900      21708       1.56  12056   1 svchost
    168      10     2260       9868       0.11  12392   1 svchost
    179      10     1956       6836             13336   0 svchost
    283      14     3412      15836       0.92  13752   1 svchost
    173       9     1900       7324             13904   0 svchost
    485      18     5020      12660             13964   0 svchost
    158      42     1692       6332             15384   0 svchost
    150      11     2332      10180       0.95  16412   1 svchost
    249      16     4056      15540             17948   0 svchost
    226      12     3052      12160             18312   0 svchost
    139       9     3148       9340             18760   0 svchost
    129       9     1560       5748             18808   0 svchost
    127       8     1464       6392             19244   0 svchost
    499      19     5548      20148             20504   0 svchost
    197      11     1988       9192             20860   0 svchost
    288      17     4412      14596             21512   0 svchost
    291      15     3684      19752       0.16  21540   1 svchost
    222      13     3076      12432             21608   0 svchost
    447      25     7724      19384             22032   0 svchost
    224      15     2820       7440             22052   0 svchost
    436      27     3824      12572             22140   0 svchost
    122       8     1320       6496             24728   0 svchost
    220      11     2204       9860             27032   0 svchost
    159      11     2088       7092             27576   0 svchost
    283      15     2804      11960             29248   0 svchost
    123       8     1268       5560             31748   0 svchost
    184      10     1956       9152             32100   0 svchost
    597      30    41184      37016              5752   0 SWVisualize.Queue.Server
    627      32    40996      37680              6060   0 SWVisualize.Queue.Server
   7649       0       40        148                 4   0 System
   1412      63    69424       2696       0.63  18172   1 SystemSettings
    640      28     9300      35008       3.86  28900   1 SystemSettingsBroker
    365      48    12564      22804       4.58  10360   1 taskhostw
    132       8     1344       5396              4780   0 TbtP2pShortcutService
   1017      41    47884      64300      19.16  13656   1 TextInputHost
    311      14     4632      16984             10784   0 uhssvc
    150      10     1912       9096              4660   1 unsecapp
    140       9     1692       7980       0.23  15928   1 unsecapp
    148      10     2912       8408       0.05   6452   1 UserOOBEBroker
    181      10     2068       8192              7124   1 vncagent
    242      13    11320      10872              5880   0 vncserver
    258      21     5844      17476       0.56  11136   1 vncserverui
    260      15    13036      14580              5900   0 WavesAudioService
   1776      33   141708      29228      17.17  15768   1 WavesSvc64
    595      30    19184     261248              5892   0 WavesSysSvc64
    896      38    17196      56052      26.84  12116   1 Widgets
    340      19     5020      20884       0.50  21104   1 WidgetService
   1527      52   180720     160220       0.91  33832   1 WindowsTerminal
    146      12     1532       5924               960   0 wininit
    285      14     2708      10116              1200   1 winlogon
   4326      96   333928     265616      67.05  17256   1 WINWORD
    507      29    40556      27412              6672   0 WmiPrvSE
    185      12     5252      13192             10616   0 WmiPrvSE
    284      15     2972      12728              6036   0 WMIRegistrationService
    473      21     6188      20004              6252   0 wslservice
    763      15    11228       9076              1400   0 WUDFHost
    455      21    14036      23416              3504   0 WUDFHost
```

---

* pwd
```
PS C:\Users\jrichar7> pwd

Path
----
```

---

* git clone
```
PS C:\Users\jrichar7> git clone https://github.com/kevinwlu/iot.git
Cloning into 'iot'...
remote: Enumerating objects: 24411, done.
remote: Counting objects: 100% (5460/5460), done.
remote: Compressing objects: 100% (1619/1619), done.
remote: Total 24411 (delta 3093), reused 5404 (delta 3066), pack-reused 18951 (from 1)
Receiving objects: 100% (24411/24411), 29.15 MiB | 5.67 MiB/s, done.
Resolving deltas: 100% (15792/15792), done.
```

---

* cd iot
* ls
```
PS C:\Users\jrichar7> cd iot
PS C:\Users\jrichar7\iot> ls


    Directory: C:\Users\jrichar7\iot


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         9/28/2024   5:54 PM                apps
d-----         9/28/2024   5:54 PM                cases
d-----         9/28/2024   5:54 PM                design
d-----         9/28/2024   5:54 PM                economics
d-----         9/28/2024   5:54 PM                health
d-----         9/28/2024   5:54 PM                hype
d-----         9/28/2024   5:54 PM                lesson1
d-----         9/28/2024   5:54 PM                lesson10
d-----         9/28/2024   5:54 PM                lesson11
d-----         9/28/2024   5:54 PM                lesson2
d-----         9/28/2024   5:54 PM                lesson3
d-----         9/28/2024   5:54 PM                lesson4
d-----         9/28/2024   5:54 PM                lesson5
d-----         9/28/2024   5:54 PM                lesson6
d-----         9/28/2024   5:54 PM                lesson7
d-----         9/28/2024   5:54 PM                lesson8
d-----         9/28/2024   5:54 PM                lesson9
d-----         9/28/2024   5:54 PM                make
d-----         9/28/2024   5:54 PM                projects
d-----         9/28/2024   5:54 PM                special_problems
d-----         9/28/2024   5:54 PM                standards
d-----         9/28/2024   5:54 PM                systems
d-----         9/28/2024   5:54 PM                tools
-a----         9/28/2024   5:54 PM          20558 README.md
```

---

* cd
* df
```
PS C:\Users\jrichar7\iot> cd
PS C:\Users\jrichar7\iot> df
Filesystem     1K-blocks      Used Available Use% Mounted on
C:/msys64      497319932 262168804 235151128  53% /
```
---
* mkdir demo
```
PS C:\Users\jrichar7\iot> mkdir demo


    Directory: C:\Users\jrichar7\iot


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         9/28/2024   5:59 PM                demo

```
---
* cd demo   
* nano file   
![image](https://github.com/user-attachments/assets/37c8199f-4706-4980-8591-7e99857661d2)

---
Next, I created three txt files (testfile, testfile1, and testfile2) to run the following commands. I saved them in the demo directory (that is, C:\Users\jrichar7\iot\demo>)
*  cat file   
  This command is used to view the contents of the file. Since the testfile.txt had the contents "testfile", this was displayed
![Screenshot 2024-10-06 011247](https://github.com/user-attachments/assets/8d3e42dc-089a-4e85-91e0-c6fe6980a92b)   
---
* cp file file1
To run the cp command, I thought it would be a good idea to first display the original contents of each txt file before making any changes:   
![Screenshot 2024-10-06 011603](https://github.com/user-attachments/assets/6328d36f-a0a1-43e4-b30a-aea0bc80b9fe)   

Then I performed `cp testfile.txt testfile1.txt` and then `cat testfile1.txt` to verify that the contents of testfile.txt were copied to testfile1.txt:

![Screenshot 2024-10-06 011904](https://github.com/user-attachments/assets/376f5069-cb4b-4d82-b8a0-a62104fef9b3)   

---
* mv file file1   
This command either renames or moves a file. To demonstrate this, I performed `mv testfile.txt new_testfile.txt` and it renamed the file as shown in the directory of 'demo':
```
C:\Users\jrichar7\iot\demo>dir
 Volume in drive C is OS
 Volume Serial Number is D208-E3B0

 Directory of C:\Users\jrichar7\iot\demo

10/06/2024  01:23 AM    <DIR>          .
09/28/2024  05:59 PM    <DIR>          ..
10/06/2024  01:05 AM                 8 new_testfile.txt
10/06/2024  01:18 AM                 8 testfile1.txt
10/06/2024  01:05 AM                 9 testfile2.txt
               3 File(s)             25 bytes
               2 Dir(s)  257,700,794,368 bytes free
```
---
* rm file
This command removes a file, so I tested this using `rm new_testfile.txt:   
```
C:\Users\jrichar7\iot\demo>rm new_testfile.txt

C:\Users\jrichar7\iot\demo>dir
 Volume in drive C is OS
 Volume Serial Number is D208-E3B0

 Directory of C:\Users\jrichar7\iot\demo

10/06/2024  01:27 AM    <DIR>          .
09/28/2024  05:59 PM    <DIR>          ..
10/06/2024  01:18 AM                 8 testfile1.txt
10/06/2024  01:05 AM                 9 testfile2.txt
               2 File(s)             17 bytes
               2 Dir(s)  257,715,970,048 bytes free
```
---
* clear
This command cleared the previous output from the terminal:   
![Screenshot 2024-10-06 013112](https://github.com/user-attachments/assets/4704d589-872a-4df4-a0e0-14b9da01de9d)

---
* man uname   
`man` is not a command in Windows, but it is used to display the user manual for Unix OS. Instead, I used `help`:   
![Screenshot 2024-10-06 013535](https://github.com/user-attachments/assets/c6f3a6fd-7400-4405-9753-5e8cc5b70cd8)
---
* uname -a
```
C:\Users\jrichar7\iot\demo>uname -a
MSYS_NT-10.0-22631 Jernique 3.3.6-341.x86_64 2022-09-06 08:02 UTC x86_64 Msys
```
---
* ifconfig
Similarly, ifconfig is unique to Unix systems, while ipconfig is specific to Windows   
```
C:\Users\jrichar7\iot\demo>ifconfig
'ifconfig' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\jrichar7\iot\demo>ipconfig

Windows IP Configuration


Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2803:1500:1c00:d143:fa30:d29e:e820:46c
   Temporary IPv6 Address. . . . . . : 2803:1500:1c00:d143:82b:cc94:3672:acb0
   Link-local IPv6 Address . . . . . : fe80::a80a:2ddd:3dbd:7672%2
   IPv4 Address. . . . . . . . . . . : 192.168.100.129
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::1%2
                                       192.168.100.1
```
---
* ping localhost
```
C:\Users\jrichar7\iot\demo>ping localhost

Pinging Jernique [::1] with 32 bytes of data:
Reply from ::1: time<1ms
Reply from ::1: time<1ms
Reply from ::1: time<1ms
Reply from ::1: time<1ms

Ping statistics for ::1:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 0ms, Maximum = 0ms, Average = 0ms
```
---
* netstat
```
C:\Users\jrichar7\iot\demo>netstat

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    127.0.0.1:4767         Jernique:49954         ESTABLISHED
  TCP    127.0.0.1:49954        Jernique:4767          ESTABLISHED
  TCP    192.168.100.129:49459  172.172.255.218:https  ESTABLISHED
  TCP    192.168.100.129:52859  52.109.13.13:https     ESTABLISHED
  TCP    192.168.100.129:54569  162.159.135.234:https  ESTABLISHED
  TCP    192.168.100.129:54575  13.71.196.252:8883     ESTABLISHED
  TCP    192.168.100.129:57644  52.96.122.34:https     ESTABLISHED
  TCP    192.168.100.129:57646  52.109.13.13:https     ESTABLISHED
  TCP    192.168.100.129:58628  lb-140-82-114-25-iad:https  ESTABLISHED
  TCP    192.168.100.129:58641  52.167.161.91:https    TIME_WAIT
  TCP    192.168.100.129:58652  20.127.250.238:https   ESTABLISHED
  TCP    192.168.100.129:58664  51.104.15.253:https    ESTABLISHED
  TCP    192.168.100.129:58666  bingforbusiness:https  ESTABLISHED
  TCP    192.168.100.129:58667  bingforbusiness:https  ESTABLISHED
  TCP    192.168.100.129:58668  bingforbusiness:https  ESTABLISHED
  TCP    192.168.100.129:58671  bingforbusiness:https  ESTABLISHED
  TCP    192.168.100.129:58673  192.168.100.229:ms-do  SYN_SENT
  TCP    [2803:1500:1c00:d143:82b:cc94:3672:acb0]:58651  vj-in-xbc:5228         ESTABLISHED
  TCP    [2803:1500:1c00:d143:82b:cc94:3672:acb0]:58661  [2606:4700:4400::6812:202f]:https  ESTABLISHED
  TCP    [2803:1500:1c00:d143:82b:cc94:3672:acb0]:58663  [2606:4700:4400::ac40:9bd1]:https  ESTABLISHED
  TCP    [2803:1500:1c00:d143:82b:cc94:3672:acb0]:58669  [2600:1f18:24e6:b902:a46c:a4a6:87fe:c14c]:https  ESTABLISHED
```
---




