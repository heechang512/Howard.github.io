```python
!pip install dart-fss
```

    Defaulting to user installation because normal site-packages is not writeable
    Collecting dart-fss
      Downloading dart_fss-0.4.4-py3-none-any.whl (141 kB)
         -------------------------------------- 141.2/141.2 kB 4.2 MB/s eta 0:00:00
    Collecting fake-useragent>=1.0
      Downloading fake_useragent-1.3.0-py3-none-any.whl (15 kB)
    Requirement already satisfied: requests in c:\programdata\anaconda3\lib\site-packages (from dart-fss) (2.28.1)
    Collecting halo
      Downloading halo-0.0.31.tar.gz (11 kB)
      Preparing metadata (setup.py): started
      Preparing metadata (setup.py): finished with status 'done'
    Requirement already satisfied: numpy in c:\users\howard\appdata\roaming\python\python39\site-packages (from dart-fss) (1.23.5)
    Requirement already satisfied: beautifulsoup4 in c:\programdata\anaconda3\lib\site-packages (from dart-fss) (4.11.1)
    Requirement already satisfied: appdirs in c:\programdata\anaconda3\lib\site-packages (from dart-fss) (1.4.4)
    Requirement already satisfied: tqdm in c:\programdata\anaconda3\lib\site-packages (from dart-fss) (4.64.1)
    Requirement already satisfied: pandas in c:\programdata\anaconda3\lib\site-packages (from dart-fss) (1.4.4)
    Collecting arelle-release
      Downloading arelle_release-2.17.4-py3-none-any.whl (8.3 MB)
         ---------------------------------------- 8.3/8.3 MB 9.3 MB/s eta 0:00:00
    Collecting xmltodict
      Using cached xmltodict-0.13.0-py2.py3-none-any.whl (10.0 kB)
    Collecting importlib-resources>=5.0
      Downloading importlib_resources-6.1.1-py3-none-any.whl (33 kB)
    Requirement already satisfied: python-dateutil==2.* in c:\programdata\anaconda3\lib\site-packages (from arelle-release->dart-fss) (2.8.2)
    Requirement already satisfied: pyparsing==3.* in c:\programdata\anaconda3\lib\site-packages (from arelle-release->dart-fss) (3.0.9)
    Requirement already satisfied: certifi in c:\programdata\anaconda3\lib\site-packages (from arelle-release->dart-fss) (2022.9.14)
    Requirement already satisfied: openpyxl==3.* in c:\programdata\anaconda3\lib\site-packages (from arelle-release->dart-fss) (3.0.10)
    Requirement already satisfied: lxml==4.* in c:\programdata\anaconda3\lib\site-packages (from arelle-release->dart-fss) (4.9.1)
    Requirement already satisfied: regex in c:\programdata\anaconda3\lib\site-packages (from arelle-release->dart-fss) (2022.7.9)
    Collecting isodate==0.*
      Downloading isodate-0.6.1-py2.py3-none-any.whl (41 kB)
         ---------------------------------------- 41.7/41.7 kB 2.0 MB/s eta 0:00:00
    Requirement already satisfied: six in c:\users\howard\appdata\roaming\python\python39\site-packages (from isodate==0.*->arelle-release->dart-fss) (1.15.0)
    Requirement already satisfied: et_xmlfile in c:\programdata\anaconda3\lib\site-packages (from openpyxl==3.*->arelle-release->dart-fss) (1.1.0)
    Requirement already satisfied: soupsieve>1.2 in c:\programdata\anaconda3\lib\site-packages (from beautifulsoup4->dart-fss) (2.3.1)
    Collecting log_symbols>=0.0.14
      Downloading log_symbols-0.0.14-py3-none-any.whl (3.1 kB)
    Collecting spinners>=0.0.24
      Downloading spinners-0.0.24-py3-none-any.whl (5.5 kB)
    Requirement already satisfied: termcolor>=1.1.0 in c:\users\howard\appdata\roaming\python\python39\site-packages (from halo->dart-fss) (1.1.0)
    Requirement already satisfied: colorama>=0.3.9 in c:\programdata\anaconda3\lib\site-packages (from halo->dart-fss) (0.4.5)
    Requirement already satisfied: pytz>=2020.1 in c:\users\howard\appdata\roaming\python\python39\site-packages (from pandas->dart-fss) (2023.3)
    Requirement already satisfied: idna<4,>=2.5 in c:\programdata\anaconda3\lib\site-packages (from requests->dart-fss) (3.3)
    Requirement already satisfied: charset-normalizer<3,>=2 in c:\programdata\anaconda3\lib\site-packages (from requests->dart-fss) (2.0.4)
    Requirement already satisfied: urllib3<1.27,>=1.21.1 in c:\programdata\anaconda3\lib\site-packages (from requests->dart-fss) (1.26.11)
    Requirement already satisfied: zipp>=3.1.0 in c:\programdata\anaconda3\lib\site-packages (from importlib-resources>=5.0->fake-useragent>=1.0->dart-fss) (3.8.0)
    Building wheels for collected packages: halo
      Building wheel for halo (setup.py): started
      Building wheel for halo (setup.py): finished with status 'done'
      Created wheel for halo: filename=halo-0.0.31-py3-none-any.whl size=11242 sha256=f520efb47218ef48c29a9e0507fcfee4b6501acb1a8d9f44c9cff75d2f42eeac
      Stored in directory: c:\users\howard\appdata\local\pip\cache\wheels\bb\85\47\b7c7338ab52808105f937bd8c04aec5d98a543311ac2c8bed2
    Successfully built halo
    Installing collected packages: spinners, xmltodict, log_symbols, isodate, importlib-resources, halo, fake-useragent, arelle-release, dart-fss
    Successfully installed arelle-release-2.17.4 dart-fss-0.4.4 fake-useragent-1.3.0 halo-0.0.31 importlib-resources-6.1.1 isodate-0.6.1 log_symbols-0.0.14 spinners-0.0.24 xmltodict-0.13.0
    

    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
      WARNING: The script arelleCmdLine.exe is installed in 'C:\Users\Howard\AppData\Roaming\Python\Python39\Scripts' which is not on PATH.
      Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -rotobuf (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow (c:\users\howard\appdata\roaming\python\python39\site-packages)
    WARNING: Ignoring invalid distribution -ensorflow-intel (c:\users\howard\appdata\roaming\python\python39\site-packages)
    


```python

```


```python
import dart_fss as dart_fss
import pandas as pd

api_key = 'd18890b6201d8cb1c547833081c7369ac0b52e18'
dart_fss.set_api_key(api_key=api_key)

corp_list = dart_fss.get_corp_list()

corp_list.corps
```


    Output()



    Output()



    Output()





    [[00434003]다코,
     [00434456]일산약품,
     [00430964]굿앤엘에스,
     [00432403]한라판지,
     [00388953]크레디피아제이십오차유동화전문회사,
     [00179984]연방건설산업,
     [00420143]브룩스피알아이오토메이션잉크,
     [00401111]매경아이비아이,
     [00435534]캐드뱅크,
     [00430186]엠와이오피삼차유동화전문유한회사,
     [00430201]엠와이오피이차유동화전문유한회사,
     [00430210]엠와이오피일차유동화전문유한회사,
     [00430229]포스미디어,
     [00140432]축복할렐루야,
     [00426208]한국전자화학,
     [00433262]ConnachtCapitalMarketInvestmentLtd.,
     [00433749]선진아이티,
     [00433785]팀스코리아,
     [00196079]에넥스하이테크,
     [00435048]세이스텝바이스텝혼합형펀드,
     [00435057]유리알파헷지채권혼합형펀드,
     [00108843]한기술정보통신,
     [00443232]다움종합건설,
     [00248293]한국애치슨,
     [00455662]고은상사,
     [00149318]조흥종합건설,
     [00451347]유니즈유통,
     [00415105]창대화장품,
     [00420824]문화종합건설,
     [00389439]한국종합미디어,
     [00454016]아이펜텍,
     [00452072]대홍염공,
     [00437602]지오항공여행사,
     [00365518]헤이아니타코리아,
     [00246967]태산산업개발,
     [00445559]군포종합시장,
     [00444657]기우,
     [00448936]라시도,
     [00405658]예전미디어,
     [00410818]세미가,
     [00416061]대닉스,
     [00448909]인포핸드,
     [00445407]지현개발,
     [00421647]한국부동산신탁제일차유동화전문유한회사,
     [00421425]ISCCaymanLtd.,
     [00423265]연산,
     [00423292]씨케이알유동화전문유한회사,
     [00420602]디에스피,
     [00307505]LOMBARDKOREAILIMITED,
     [00218229]승진씨앤씨,
     [00241397]우신투자자문,
     [00421896]외환카드제오차유동화전문유한회사,
     [00365712]태연,
     [00388616]글로벌금강제일차유동화전문유한회사,
     [00230407]글로벌렌탈,
     [00423566]뤼미에르에셋,
     [00423274]바사라엔터테인먼트,
     [00419688]대백유동화전문유한회사,
     [00419712]아이키키,
     [00414665]진명씨앤씨,
     [00421869]한경핫벤처,
     [00421957]우리부동산제일차유동화전문유한회사,
     [00255442]영진상운,
     [00427517]한국토지신탁제오차유동화전문유한회사,
     [00376152]다드림커뮤니케이션,
     [00382241]ARISAIGASIANSMALLCOMPANIESFUND(L)BHD,
     [00431501]싱가포르개발은행서울지점,
     [00434270]삼성인덱스프리미엄30혼합형뮤추얼펀드,
     [00434289]KTB혼합형펀드,
     [00434298]KTB플러스찬스혼합형펀드,
     [00434313]KTB포트폴리오스타혼합형펀드,
     [00434322]KTB에버스타혼합형펀드,
     [00429463]나노이앤씨,
     [00429515]지산엔터프라이즈,
     [00432175]유아이에스코리아,
     [00387033]트리플에스유동화전문유한회사,
     [00384045]크레디피아제이십일차유동화전문유한회사,
     [00431608]싱가포르개발은행,
     [00431705]엘지팩토링제일차유동화전문유한회사,
     [00430256]이피에스뱅크,
     [00431167]이라이프네트워크,
     [00432315]덕성,
     [00413134]타오건설,
     [00435376]장원코리아,
     [00110909]대신통상,
     [00245995]삼광제지공업,
     [00220695]서울교육,
     [00211794]보성패션,
     [00454496]넥스탑,
     [00455592]마니빌,
     [00370796]제이엘코프,
     [00199401]컴마을,
     [00369596]삼신크리에이션,
     [00210078]호한통상,
     [00363398]케이엠티,
     [00110042]대백가구,
     [00364324]청빛산업개발,
     [00248017]삼양전자,
     [00452179]숭민코리아유통,
     [00413754]유오티앤씨,
     [00343163]한라스페코중공업,
     [00452513]알본,
     [00435978]상일디지털,
     [00368153]서전어패럴,
     [00455149]웰비스트랜스,
     [00249946]한국키엔스,
     [00110839]대신생명보험,
     [00293798]대성메디테크,
     [00113119]대한알루미늄공업,
     [00424389]남성엠케이,
     [00424486]씨엠액텍,
     [00224734]한국부동산신탁,
     [00197713]주은산업,
     [00421948]신엘지프라이머리제이차유동화전문유한회사,
     [00422381]데코제일차유동화전문유한회사,
     [00350446]뉴스테이트삼차모기지유동화전문유한회사,
     [00396642]엘지수퍼센터,
     [00425449]아이클릭세븐,
     [00425458]월드인코레스,
     [00425333]코리아픽시컴,
     [00424617]산은부동산제사차유동화전문유한회사,
     [00424006]글로벌자이언트시스템,
     [00424051]신클레어,
     [00403599]에이에스피기업구조조정전문,
     [00425519]Marubeni-ItochuSteelInc.,
     [00224585]신한,
     [00429524]우리모아제이차유동화전문유한회사,
     [00429533]글로벌사모안정혼합형펀드,
     [00432722]파워외환카드제팔차유동화전문유한회사,
     [00432786]파워외환카드제오차유동화전문유한회사,
     [00429728]영퓨처,
     [00428668]코로볼틴펀드리미티드,
     [00430751]대창크랑크,
     [00385372]허츠제일차유동화전문유한회사,
     [00431680]새암교육,
     [00386308]반지종합상가,
     [00256450]동서산업건설(가칭),
     [00290816]대우종합기계(가칭),
     [00291532]대우조선공업(가칭),
     [00127990]삼일상호저축은행,
     [00431565]케이디에스에스,
     [00399959]비젼케이파트너스,
     [00430238]리버랜드,
     [00263034]동양선재,
     [00205298]춘천미도파,
     [00431042]거버너스M&A사모펀드3호,
     [00348715]아이앤비골드문브이에이치,
     [00447964]체리미디어,
     [00448361]경원하이텍,
     [00185851]중원화학,
     [00445735]나크나인,
     [00385770]동남해상관광호텔,
     [00319245]한성선박,
     [00126502]삼성콘크리트공업,
     [00363440]엠알더블유테크노로지,
     [00445522]제이에이치홀딩스,
     [00320302]동연산업,
     [00444958]우양주택건설,
     [00441836]해진하우징,
     [00445203]대림전자,
     [00445629]효헌산업,
     [00454052]우림산업개발,
     [00454414]에이스하이테크,
     [00196857]해표푸드서비스,
     [00413383]에프씨산업,
     [00225098]극동뉴메릭,
     [00410304]서울드림랜드,
     [00310998]한국미라이공업,
     [00415114]21세기화장품,
     [00451000]광명산업,
     [00369985]다음솔루션,
     [00199809]이성화학,
     [00371670]정우조명,
     [00401430]모바일웰컴,
     [00247027]푸른건설,
     [00144058]월다크,
     [00416867]길도건업,
     [00456263]원일스포지움,
     [00436339]용인자원,
     [00120748]마산강관,
     [00386724]세창철강공업,
     [00255390]재무와정보,
     [00455547]대양중공업,
     [00233398]이에이지씨,
     [00405065]페타코페트로륨,
     [00425537]MarubeniCorporation,
     [00424158]캐피탈라인,
     [00100920]건설증권,
     [00370167]일진전자통신,
     [00409131]오픈솔루션,
     [00424194]AMERICAORIENTALGROUP,
     [00364713]mvp창업투자,
     [00408901]라이져,
     [00161170]한라시멘트,
     [00423557]한국알리안츠화재해상보험,
     [00307444]코리아벌처투자,
     [00370468]티에스케이지,
     [00424547]메리츠투자자문,
     [00424219]텔레닉스,
     [00424185]유니텍워터시스템즈,
     [00424556]거륜씨앤씨,
     [00121631]문화,
     [00424866]모비도미,
     [00424884]에이치케이인베스트먼트유동화전문유한회사,
     [00424927]LiquidmetalTechnologies,
     [00423797]모멘타(케이만),
     [00433350]KTB프라임8호혼합형사모펀드,
     [00433369]유리명품장기채권형사모펀드3호,
     [00433378]유리유니콘채권혼합형펀드,
     [00433387]맥쿼리아이엠엠프라임7호채권형사모펀드,
     [00433420]마이에셋애국성장형이호펀드,
     [00433457]채권플러스알파2호펀드,
     [00433466]마이다스사모프라임안정형2호펀드,
     [00376073]테크포인트,
     [00234306]부국개발,
     [00429418]세닥에듀케이션,
     [00429977]에이치엘홀딩스에스에이,
     [00340786]크레디리요네증권,
     [00218928]케이티인더스트리,
     [00106793]김천상호저축은행,
     [00378886]이화홀딩스,
     [00433484]미래에셋유니온사모혼합형펀드2호,
     [00433493]맥쿼리아이엠엠액티브채권형사모펀드3호,
     [00433509]맥쿼리아이엠엠프라임6호혼합형사모펀드,
     [00433518]유리명품장기채권형사모펀드2호,
     [00406596]신우쉬핑,
     [00443001]동흥컨설팅,
     [00363741]디조콤,
     [00436375]맘모스산업개발,
     [00222277]아성,
     [00446284]디토정보기술,
     [00446682]오우디앤씨,
     [00139995]에어웨이엑스프레스,
     [00444602]탑월드,
     [00446433]옥시큐어,
     [00150314]진로종합유통,
     [00231840]케이에프텍,
     [00236243]나토상사,
     [00309479]지오이네트,
     [00447034]이십일세기종합건설,
     [00447496]일현건설,
     [00300928]삼영기공,
     [00317566]삼능주택,
     [00412001]동해,
     [00155407]풍광직물,
     [00443542]기성텍스타일,
     [00179726]제텍스바론,
     [00300982]국제개발,
     [00298818]유유후마킬라,
     [00424644]피앤씨미디어,
     [00350570]비앤에프투자자문,
     [00424316]한국부동산신탁제이차유동화전문유한회사,
     [00368551]에이텍,
     [00424307]덕경종합건설,
     [00425078]글로벌스페셜혼합형사모펀드,
     [00154499]태화,
     [00424653]씨앤앰유동화전문유한회사,
     [00414522]온누리방송,
     [00425120]케이티엠,
     [00356723]아이앤비골드문컨설팅,
     [00375506]동국제강제일차유동화전문유한회사,
     [00424769]밸류노믹스기업구조조정전문회사,
     [00223300]조창,
     [00378178]테크노켐,
     [00360294]영지통상,
     [00425209]RosewellConsulting&InvestmentLtd.,
     [00433527]유리시티즌장기채권형사모펀드,
     [00433536]KTB장기채권형사모펀드3호,
     [00433545]KTB장기채권형사모펀드4호,
     [00433554]맥쿼리아이엠엠포세이돈채권형사모펀드4호,
     [00433563]마이에셋애국안정형1호펀드,
     [00434702]노보스,
     [00434711]세이유니온채권혼합형사모펀드,
     [00434720]LG드림혼합형펀드,
     [00434739]알파그로스주식형펀드,
     [00434748]유리알파헷지채권혼합형사모펀드,
     [00434757]알파헷지이기욱혼합형펀드,
     [00434775]맥쿼리IMM홀인원채권형펀드,
     [00434793]유리시장중립채권형사모펀드,
     [00434809]유리알파30채권혼합형사모펀드,
     [00432573]파워외환카드제사차유동화전문유한회사,
     [00432607]파워외환카드제이차유동화전문유한회사,
     [00432643]케드제이차유동화전문유한회사,
     [00323390]굿윌경영자문,
     [00412861]국제금속산업,
     [00443913]덕정무역,
     [00315179]삼성코닝마이크로옵틱스,
     [00165264]혜성건설,
     [00368171]코스모에쿼티파트너스,
     [00369480]경빈,
     [00446196]내외시스템,
     [00108311]태승어패럴,
     [00105615]금동조명,
     [00360197]태광정밀공업,
     [00360364]게르마니셀로이드코리아,
     [00366720]청우제강,
     [00273536]필리아텔레콤,
     [00443375]진도개발,
     [00447511]만남과축복,
     [00403872]영상산업,
     [00243793]카이저산업,
     [00441757]쌈솔,
     [00445221]링크테크21,
     [00448769]건화메디팜,
     [00351357]윈윈창업투자,
     [00371333]지티웹코리아,
     [00392716]트랜스미디어매니지먼트,
     [00424398]남성유통,
     [00380322]무지개유동화전문유한회사,
     [00387264]엘지화학제일차유동화전문유한회사,
     [00425379]페가수스캐피탈아시아,
     [00421595]한솔케미언스제일차유동화전문유한회사,
     [00128564]삼천리M&C,
     [00304757]넥스트디앤드에스,
     [00407142]드림라인제일차유동화전문유한회사,
     [00408044]동국산업제일차유동화전문유한회사,
     [00112387]휴먼이노텍,
     [00423539]자도,
     [00103981]광전자INT,
     [00416478]굿케이디비제삼차유동화전문유한회사,
     [00418801]신엑스퍼트유동화전문,
     [00419332]비발디제일차유동화전문유한회사,
     [00418078]두산위브유동화전문유한회사,
     [00419651]코오롱폴리스유동화전문유한회사,
     [00251695]메디캐피탈,
     [00432661]파워외환카드제삼차유동화전문유한회사,
     [00430858]에이치에스비프로퍼티원인베스트먼트유동화전문유한회사,
     [00432670]서상금속,
     [00434827]세이한가족주식형펀드,
     [00434872]알파크레디트플러스채권형펀드,
     [00434881]알파국공채채권형사모펀드,
     [00434906]세이에이스알파혼합형펀드,
     [00434915]맥쿼리IMM코리아플러스채권형펀드,
     [00434924]맥쿼리IMM마켓뉴트럴혼합형사모펀드,
     [00434933]세이원채권형펀드,
     [00435093]그레이터차이나1호사모펀드,
     [00435109]윌러스,
     [00431820]디베스트사모엠엔에이펀드일호,
     [00398525]미래에셋프리미어전환혼합형이호펀드,
     [00260967]디지텔,
     [00378956]유리세이프롱숏채권혼합형펀드,
     [00164104]리젠트화재보험,
     [00101266]경남리스금융,
     [00412834]굿머니,
     [00226343]한소닉테크,
     [00150147]지산개발,
     [00416937]지구환경산업,
     [00132497]성도통상,
     [00216461]에프샵,
     [00369301]근영전자통신,
     [00360106]보해주정,
     [00183710]영화,
     [00410483]윈스텍,
     [00409928]조한도시개발,
     [00209647]대웅전기산업,
     [00370316]해피라인,
     [00134246]세원건설,
     [00444806]린나이씨에스,
     [00233112]성우전자,
     [00297758]에스더블유씨코퍼레이션,
     [00450986]미도산업개발,
     [00442206]덕성섬유,
     [00361664]기흥종합건설,
     [00370334]이에이치상사,
     [00432616]웨이브티브이,
     [00444073]축산농협안산연합사료,
     [00405436]유니크,
     [00414319]송학장갑,
     [00261610]위트비전,
     [00362432]월드무역,
     [00415293]오픈테크,
     [00413204]아피아,
     [00413277]차세대정보통신,
     [00268455]조흥신탁유동화전문회사,
     [00273606]오토일천구백구십구의일유동화전문유한회사,
     [00303369]한국토지신탁제이차유동화전문유한회사,
     [00317043]포커스제1차유동화전문유한회사,
     [00328517]베스트이지제일차유동화전문유한회사,
     [00341776]모비스코람유동화전문유한회사,
     [00362131]아이에스피,
     [00427492]한실흥산,
     [00363413]아이티엔방송,
     [00302829]슈퍼데크코리아,
     [00426758]산은부동산제오차유동화전문유한회사,
     [00427474]덕화산업,
     [00428695]국민카드이천이의일유동화전문유한회사,
     [00366508]마일스톤벤처투자,
     [00402208]에스비아이코리아,
     [00175021]씨티은행,
     [00429250]AllianzFinanceB.V.,
     [00425777]동의보감유동화전문유한회사,
     [00109125]세화기술투자,
     [00388810]미래에셋프리미어혼합형펀드,
     [00383426]마이다스차익거래안정혼합형펀드,
     [00146676]아이씨켐,
     [00338152]소프트윈,
     [00438902]신하나로유동화전문유한회사,
     [00432856]벽산건설블루밍제일차유동화전문유한회사,
     [00431033]이천일아울렛제일차유동화전문유한회사,
     [00240866]씨마유통,
     [00440934]캠앤아이코리아,
     [00440952]제이경영컨설팅,
     [00435905]이리연료,
     [00435598]태거산업,
     [00350136]마인드텔,
     [00350206]엘파오벤쳐캐피탈,
     [00268288]심스밸리,
     [00105846]LGEI,
     [00350756]유리크레디트회사채혼합형펀드,
     [00149497]알파캐피탈,
     [00264778]유니씨앤티,
     [00289227]미래에셋파이오니어벤처코스닥펀드,
     [00449184]디에이치파트너스,
     [00369028]근하종합개발호텔엑스포,
     [00152491]코락,
     [00445601]터보엔지니어링,
     [00407610]알파엔지니어링,
     [00146241]명성건설,
     [00446071]스카이함백,
     [00368384]비에스그룹,
     [00446840]삼부이엔씨,
     [00245791]두앙종합건설,
     [00449625]신성전자,
     [00375223]한국기업금융자문,
     [00411631]고룡,
     [00256326]아성식품,
     [00367330]세원지애에이치,
     [00371838]남양주택건설,
     [00246480]이조해운,
     [00359304]한서화학,
     [00415600]대륭전자,
     [00422910]서울에프엔텍파트너스,
     [00451055]팔공산온천관광호텔,
     [00448839]택산개발,
     [00234670]동진피엠씨,
     [00224707]대흥정공,
     [00193568]신대광주택,
     [00415080]아프로시스템스,
     [00415053]화진코스메틱,
     [00414869]모비야,
     [00365527]우리켐테크,
     [00364245]ABC,
     [00364005]캐피탈아거스,
     [00413329]유니솔,
     [00215222]세화유통,
     [00252481]용강,
     [00369897]기바전자,
     [00310855]에프에스비티아이코리아,
     [00370015]디지텍,
     [00303448]알에이코프,
     [00404394]매경휴스닥,
     [00201946]한국이연,
     [00304207]한원텔레콤,
     [00305093]진우,
     [00410720]탑종합건설,
     [00354354]썬키스,
     [00311049]위슬런,
     [00412782]대산반도체,
     [00426615]네오소프트,
     [00164061]드림에스디,
     [00381659]크레디피아제십구차유동화전문,
     [00382959]콩코드캐피탈아시아,
     [00118886]에이브이씨닷컴,
     [00374835]케이씨알파트너스,
     [00115700]동성투자,
     [00389192]오엔씨네트웍스,
     [00346452]씨에스지,
     [00420356]하이페리온제이차유동화전문유한회사,
     [00425528]부산유조선,
     [00427784]목동우림루미아트유동화전문유한회사,
     [00244297]천보파이낸스,
     [00428817]나라펫,
     [00425740]하이케어시스템즈,
     [00389086]우리금융제일차유동화전문유한회사,
     [00425759]키치녹스,
     [00426721]에이치에스제일차유동화전문유한회사,
     [00426651]신드림풀유동화전문유한회사,
     [00427951]넥센캐피탈,
     [00448112]종연산업,
     [00446655]성환,
     [00357111]삼두디엔에스,
     [00360717]녹십자피디,
     [00411321]율비,
     [00193221]삼희산업,
     [00407595]아이스타뮤직,
     [00147417]전일제지,
     [00367075]신흥울테크,
     [00448501]삼양이컴,
     [00197856]전주코아호텔,
     [00378017]헬리오스기업구조조정전문회사,
     [00207384]동일상사,
     [00233927]헨켈코리아,
     [00255372]센텍,
     [00246693]태흥기업,
     [00367932]만적,
     [00334341]성신무역,
     [00190224]새한철강,
     [00448291]한림종합개발,
     [00445391]동방귀석,
     [00169321]부곡관광,
     [00434076]에이취.엠.에스,
     [00205128]서통테크놀로지,
     [00450250]한경섬유,
     [00368126]세진티앤엠,
     [00175386]경기교통,
     [00205748]강호개발,
     [00358378]만덕,
     [00221409]한국어센셜소프트웨어,
     [00414328]와우북,
     [00188061]한서시계,
     [00409982]부풍,
     [00134149]세우무역,
     [00414461]신우종합건설,
     [00304508]중원,
     [00247753]아스트로,
     [00368816]한국멀티넷,
     [00366085]넥스트미디어아이,
     [00412302]일성리조트,
     [00387246]동광산건,
     [00265050]유렉셀테크놀러지,
     [00236182]성일컴퓨텍,
     [00296555]엠에프씨,
     [00327226]얼라이언스시스템,
     [00412852]대한주택이앤지,
     [00143970]원창판지,
     [00301404]한국피시,
     [00109541]대륙공업,
     [00404880]디지털테크놀러지,
     [00393858]드림데이타,
     [00385123]리첸시아유동화전문유한회사,
     [00429010]코리아페이넷,
     [00424963]디더블유씨유동화전문유한회사,
     [00425768]티지일차유동화전문유한회사,
     [00426749]피앤지정보통신,
     [00330415]인바인,
     [00150794]진흥주택,
     [00429038]굿앤세이프,
     [00421081]디바이너,
     [00361734]케이아이티창업투자,
     [00388768]외환카드제사차유동화전문유한회사,
     [00425421]오프마이십일,
     [00421850]창신테크,
     [00425315]파워엑시스,
     [00427580]삼성프론티어제십이차유동화전문유한회사,
     [00425218]쓰리엔제이차유동화전문유한회사,
     [00106951]낙산관광호텔,
     [00395661]현지개발,
     [00275118]케이티비벤처벌처일호펀드,
     [00295389]메타텍,
     [00389147]골든보우창업투자,
     [00126803]삼아,
     [00242341]에스엠아이씨,
     [00440314]오토피아제팔차유동화전문유한회사,
     [00440332]니즈솔루션,
     [00441322]이나라카드,
     [00440165]히타치전선,
     [00288884]미래에셋드림파이오니어펀드,
     [00148452]GPS,
     [00156017]하나은행,
     [00261045]시스컴,
     [00437532]개풍주택개발,
     [00303095]지오스테크널러지,
     [00438753]IndusAsiaPacificFund,Ltd.,
     [00367464]지앤텍,
     [00201955]금화냉동,
     [00409849]혜성,
     [00131443]서통상사,
     [00174022]유창섬유,
     [00444763]피프,
     [00412171]모수인터내쇼날,
     [00232973]동해산업,
     [00152419]대농중공업,
     [00257413]신영팩토링,
     [00362511]승진건설,
     [00446743]아워스인베스트먼트,
     [00253055]태흥산업개발,
     [00448714]마하인더스트리,
     [00448705]모아건설,
     [00101716]경북레미콘,
     [00447876]그루빅,
     [00448671]라이프건설,
     [00217150]대진종합건설,
     [00164344]해피아이,
     [00303314]성서,
     [00451213]한신공업,
     [00407416]오랙스정유,
     [00178675]이논,
     [00367181]예들,
     [00439062]세제,
     [00413514]가인수산,
     [00127538]삼원산업,
     [00370051]유덕건설,
     [00415123]크로스전자,
     [00106012]금성텔,
     [00158495]한국아프라이드매그네틱스,
     [00299774]스타럽스,
     [00414911]텔레프리,
     [00414762]금화도시개발,
     [00234078]길정종합건설,
     [00412515]메디링스,
     [00151076]창원개발,
     [00170512]우신레저산업,
     [00370033]연이산업,
     [00406587]다른신문,
     [00413471]비투올네트,
     [00248804]성진사,
     [00359854]네투스테크놀러지,
     [00252870]동구,
     [00300432]비아이캐피탈,
     [00415938]세아개발,
     [00370714]퍼시픽스타,
     [00345693]SKIMT,
     [00426226]일신제약,
     [00426235]모아에셋,
     [00376505]그린페이퍼텍,
     [00427058]원업제이차유동화전문유한회사,
     [00427100]두손테크피아,
     [00427331]유니맥코리아,
     [00429144]아하크레딧유동화전문유한회사,
     [00429180]거버너스M&A사모펀드2호,
     [00419916]기가솔,
     [00421009]모쿠스,
     [00363796]남양산업,
     [00302148]에이팩스기술투자,
     [00426314]에스지테크놀러지,
     [00427146]도이체방크아게런던,
     [00245065]에이에스엠엘에스씨,
     [00427182]얼라이언스캐피탈파트너즈,
     [00382852]대진산업,
     [00362113]하늘사랑,
     [00220756]씨앤씨캐피탈,
     [00162319]한양상사,
     [00355511]Photronics,Inc.,
     [00400176]무빙넷,
     [00396402]슈마커코리아,
     [00439938]유케이,
     [00337977]캐피탈리서치앤매니지먼트컴퍼니,
     [00436047]월드타운,
     [00387097]센텀파크유동화전문유한회사,
     [00274410]인트빔,
     [00328100]나래소프트시스템,
     [00243845]삼광고하켐,
     [00336260]OAKMARKINTERNATIONALFUND,
     [00262026]신중앙99-1유동화전문유한회사,
     [00264431]크레디피아유동화전문,
     [00264495]중소기업유동화전문유한회사,
     [00267067]산은캐피탈제일호유동화전문유한회사,
     [00290791]국민제이차유동화전문회사,
     [00297837]국민제일차유동화전문유한회사,
     [00429162]남양씨앤씨,
     [00203643]유일냉장,
     [00450108]평산공영,
     [00171414]파산자한국산업증권,
     [00200549]대홍방직,
     [00114543]도투락,
     [00197607]해덕기업,
     [00258263]이수금속,
     [00363617]세미코리아,
     [00450287]정방종합건설,
     [00413082]성우종합건설,
     [00449537]신아토건,
     [00163071]한일염공,
     [00453239]코스모건설,
     [00414267]한국방송출판,
     [00349088]태성개발,
     [00451514]월성주택건설,
     [00386830]심도산업,
     [00410128]코리아라이닝,
     [00161198]한라종합건설,
     [00126849]삼안공영,
     [00437824]제석주택,
     [00363176]한국모빌솔루션,
     [00299871]연화상사,
     [00336686]현대티타늄,
     [00340892]한강온천,
     [00415725]나우아이엔에스,
     [00306205]디아이씨,
     [00371351]비앤에스아이엔씨,
     [00369851]창원건설,
     [00415840]알루테크,
     [00246666]대상하이디어,
     [00153296]태강산업,
     [00161268]한륙전자,
     [00210476]영신산업,
     [00365581]이사이트랩,
     [00183598]영신플랜트,
     [00417088]정연산업,
     [00415062]아코텔레콤,
     [00172529]대영,
     [00407337]프라임플러스캐피탈,
     [00405092]에스티지시큐리티,
     [00226060]보성설비,
     [00206349]록정개발,
     [00217035]신아스포츠,
     [00224318]뉴라인여신금융,
     [00424945]중소기업제삼차유동화전문유한회사,
     [00428604]알비에이,
     [00424565]체리스톤코리아,
     [00226574]세모화학,
     [00425157]리딩씨앤씨,
     [00427340]폴리코,
     [00427429]산은굿밸류제일차유동화전문유한회사,
     [00420453]이프리즘,
     [00403696]디미디어,
     [00417592]유피텍,
     [00365998]티브이가이드,
     [00412913]스타코리아웹케스팅,
     [00421355]아라정보기술,
     [00426439]코리아컨텐츠네트워크,
     [00427386]티티월드,
     [00167129]흥산건설,
     [00217707]연덕건설,
     [00426518]비추미코리아제일차유동화전문유한회사,
     [00426536]크레디피아제삼십오차유동화전문유한회사,
     [00426545]아하론제삼차유동화전문유한회사,
     [00335951]동원제일차유동화전문,
     [00436588]케이투이,
     [00435349]지영상사,
     [00331450]아주의대벤처메딕스,
     [00341952]엑스퍼트유동화전문유한회사,
     [00342739]마이에셋유동화전문유한회사,
     [00342988]한아름제2차유동화전문유한회사,
     [00436241]에셋외환카드제이차유동화전문유한회사,
     [00436269]에셋외환카드제육차유동화전문유한회사,
     [00436296]타이거유동화전문유한회사,
     [00237491]서한전자,
     [00118099]동원직물,
     [00436685]청유,
     [00437107]서울전산,
     [00436490]씨에스,
     [00436524]선암건설,
     [00435923]아세텔레콤,
     [00437541]우리엘비제칠차유동화전문유한회사,
     [00437569]지오택드레인,
     [00336385]몬덱스코리아,
     [00198253]서광티앤씨,
     [00354062]로직스컴퓨터,
     [00311818]RedTulipInvestments,
     [00452267]아이산업개발,
     [00446141]비코레트,
     [00245117]강남산업,
     [00451365]우림엔지니어링건축사사무소,
     [00263627]백현건설,
     [00413912]우연종합건설,
     [00362618]용성조선,
     [00202404]송원자동차조명,
     [00450773]태산종합건설,
     [00252852]근도물산,
     [00451879]씨에스피산업,
     [00181217]삼흥판지,
     [00375728]인터내셔날쥬피텍,
     [00445823]대륙종합건설,
     [00387167]마시나코아,
     [00256885]부천산업,
     [00452674]바롬테크,
     [00449421]대방종합건설,
     [00209230]영도섬유,
     [00412311]미디어파트너스,
     [00233741]한이해운,
     [00299400]금영,
     [00112518]대준섬유,
     [00416760]두일,
     [00397438]벽송종합건설,
     [00198615]평해건설,
     [00363228]대동제지공업,
     [00415257]동서디엔씨,
     [00369365]케미스,
     [00405126]텔리맨,
     [00415266]과일나라,
     [00361354]넷츠고,
     [00415275]동승건설,
     [00367446]주영크리에이션,
     [00415673]태광엔터프라이즈,
     [00171751]한주종합건설,
     [00416797]유정건설,
     [00193407]세광종합건설,
     [00365943]금양레포츠,
     [00363060]게임벤처,
     [00418892]마이애셋사모M&A펀드B호,
     [00418917]하나로밀레니엄,
     [00417370]메트로에이전시,
     [00427508]국민카드제십차유동화전문유한회사,
     [00367987]시봉전자,
     [00428020]두산스피리츠,
     [00382296]게토코리아,
     [00297332]AmkorTechnology,Inc.,
     [00378929]에이피엠쇼핑몰,
     [00384735]코텍,
     [00303572]아이거넷,
     [00399250]도원닷컴,
     [00434951]맥쿼리장기채권형펀드,
     [00434988]세이리딩스톡혼합형펀드,
     [00434997]세이고배당장기증권저축펀드,
     [00435002]세이고배당주식형펀드,
     [00435136]맥쿼리IMM슈페리어채권형사모펀드,
     [00434331]KTB채권형펀드,
     [00434359]글로벌퍼펙트혼합형펀드,
     [00434377]삼성중소형알짜주식형뮤추얼펀드,
     [00434386]KTB장기증권저축펀드1호,
     [00434438]KTB에이플러스2호혼합형사모펀드,
     [00286877]비비앤씨,
     [00436913]대청산업,
     [00436366]링컨아카데미,
     [00369116]디아이컨설팅,
     [00261577]네띠앙,
     [00434261]크레디피아제삼십팔차유동화전문유한회사,
     [00222204]산내들축산,
     [00436153]거장주택건설,
     [00437967]쓰리디컴넷,
     [00435914]대양식품,
     [00435899]태강건설,
     [00437383]국제전자정밀,
     [00351825]투어토털닷컴,
     [00415008]드림미르,
     [00436968]부광,
     [00436852]도원건설,
     [00436393]현우유통,
     [00261142]엘리온정보기술,
     [00439406]지석공영,
     [00421559]에쓰엠제일차자산유동화전문,
     [00387060]뉴밀레니엄코람제이차유동화전문유한회사,
     [00434067]렉스상사,
     [00446938]보나뱅크,
     [00413161]토탈메드,
     [00450409]엔트,
     [00430283]협성염공,
     [00370875]디비엔지니어링,
     [00230878]삼양텍스,
     [00409867]얄개네트워크,
     [00385044]지트랜코리아,
     [00173245]삼보,
     [00423812]국민카드제구차유동화전문유한회사,
     [00425661]국민카드제십일차유동화전문유한회사,
     [00273907]하나로제4차유동화전문회사,
     [00283533]와이디세이프유동화전문유한회사,
     [00445966]늘푸른마을,
     [00450001]이노크래프트,
     [00449555]강동종합유선방송,
     [00452443]한림하우징,
     [00366836]아이티엠,
     [00444426]코산아이엔티,
     [00261665]미광핸드백,
     [00363945]신정건설,
     [00414832]코이넬,
     [00383161]서울제일차유동화전문유한회사,
     [00163026]이지닷컴,
     [00414610]지에프엠에스,
     [00415947]언아더월드,
     [00304605]로티스,
     [00414957]이파워게이트,
     [00416229]윤진개발,
     [00120243]레이디,
     [00411659]미트마트옥션,
     [00198314]아싸,
     [00413408]웰리치개발,
     [00163965]항도종합금융,
     [00416724]아이텍테크널러지,
     [00218502]중앙제약,
     [00364175]우남산업,
     [00417422]윈로지스뉴톤보레알,
     [00417981]한국지방재정공제회,
     [00307046]창도건설,
     [00237349]부국개발,
     [00414364]유경엔지니어링,
     [00417626]한국레이저영상,
     [00414337]뷰텍,
     [00418050]씨에이블,
     [00415567]아토메가,
     [00247984]도레미농산,
     [00371494]다인개발,
     [00358147]호만기업,
     [00150554]갑을개발,
     [00305279]에버그린유동화전문유한회사,
     [00386326]맥트랜스인터내셔날,
     [00100753]거봉,
     [00204703]대산레미콘,
     [00417316]크레딧크리에이터이천이유동화전문유한회사,
     [00207959]신택,
     [00411109]바티오테크,
     [00417477]하우징그룹우신,
     [00414054]통인물류정보통신,
     [00303730]에스지에스컨테크,
     [00362229]광호,
     [00317326]펜다하우스,
     [00418430]프르덴셜어슈어런스컴퍼니리티니드,
     [00434447]KTB장기증권저축펀드,
     [00434517]삼성인덱스프리미엄주식형뮤추얼펀드,
     [00434526]KTB하이스타혼합형펀드,
     [00433721]한국광학초자,
     [00434207]광평개발,
     [00434562]KTB밸류스타혼합형펀드,
     [00434571]KTB글로벌스타주식형펀드,
     [00434580]KTB프라임4호주식형사모펀드,
     [00434599]KTB베스트바이혼합형펀드,
     [00434605]KTB하이턴펀드,
     [00434614]마이다스A등급채권혼합형펀드,
     [00435145]맥쿼리아이엠엠프라임3혼합형사모펀드,
     [00396448]피이아이코리아사모엠엔에이일호펀드,
     [00430937]아담소프트,
     [00423034]피델리티펀드,
     [00435127]유리크레디트채권혼합형펀드,
     [00434544]KTB프리미엄찬스혼합형펀드,
     [00434553]KTB에이스찬스혼합형펀드,
     [00432050]다린정보,
     [00344843]기보캐피탈제일차유동화전문유한회사,
     [00371908]엘에스에프프로퍼티투유동화전문,
     [00339090]온디지털테크,
     [00337986]캐피탈그룹인터내셔널인코포레이티드,
     [00206136]세림아이텍,
     [00440411]코스유동화전문유한회사,
     [00422309]뉴밀레니엄하나유동화전문유한회사,
     [00439257]동양정보통신M&A,
     [00439284]하이페리온제삼차유동화전문유한회사,
     [00439424]코머스에셋,
     [00435011]경동실업,
     [00428525]에스티엑스제이차유동화전문유한회사,
     [00427128]오일뱅크제삼차유동화전문유한회사,
     [00428677]케이지브이제일차유동화전문유한회사,
     [00436560]인성어패럴,
     [00440697]소프티안,
     [00439734]동양알미늄,
     [00327387]소모페스트,
     [00437611]젤존항공여행사,
     [00321064]바이오엔비텍,
     [00362557]세원반도체,
     [00224105]두원그린피아,
     [00447654]미도핸드백,
     [00453169]대영테크,
     [00371388]아이비젠,
     [00144340]한화포리마,
     [00437204]신케이에스유동화전문유한회사,
     [00443302]프라임유동화전문유한회사,
     [00436463]우영제일차유동화전문유한회사,
     [00452692]한컴리눅스,
     [00441739]두산건설제육유동화전문유한회사,
     [00441669]산은부동산제팔차유동화전문유한회사,
     [00436940]오토피아제칠차유동화전문유한회사,
     [00436959]외환카드제팔차유동화전문유한회사,
     [00427526]삼성신한아하론일차유동화전문유한회사,
     [00264705]현대유동화전문유한회사,
     [00387714]칼제일차유동화전문유한회사,
     [00300946]백두건설,
     [00402086]리엔텍,
     [00452461]대양건설,
     [00100948]건양콘크리트,
     [00365572]맥스미디어,
     [00400486]루넷,
     [00417909]충일아스콘,
     [00153816]태양연와공업,
     [00414586]제동,
     [00187637]농협축산유통,
     [00415035]동서D&S,
     [00235864]에스앤제이,
     [00416043]창영물산,
     [00174280]태화건설,
     [00417352]동방코리아,
     [00238223]영텍스타일,
     [00248530]미진시스템,
     [00234740]고려소재개발,
     [00417565]아이앤알코리아기업구조조정전문,
     [00192958]건륭실업,
     [00387459]충주공용버스터미널,
     [00415761]푸른도시개발,
     [00404011]로고스이넷,
     [00168553]대광종합건설,
     [00309804]굿윌씨앤아이,
     [00408600]아라아이디시,
     [00418731]디엠아이디,
     [00363121]웅보개발,
     [00230577]광복산업개발,
     [00295671]리빙티브이,
     [00418759]산은부동산제삼차유동화전문유한회사,
     [00211448]신라,
     [00406170]글로만,
     [00301060]서림개스실린더,
     [00242350]파인에셋홀딩스,
     [00134352]세일,
     [00420569]한일밀라노.존,
     [00422141]첼린저이차유동화전문유한회사,
     [00422178]휴민텍,
     [00419891]템플턴스트래티직이머징마켓츠펀드엘디씨,
     [00419907]신한파이낸스,
     [00310989]코오롱모터스,
     [00420976]큐마트솔루션,
     [00421072]나은미디어,
     [00423706]BystronicLaserAG,
     [00384425]코브코유동화전문유한회사,
     [00350297]칼스버그에이에스,
     [00421124]아이엠씨마케팅,
     [00434632]글로벌채권프리미엄혼합형펀드,
     [00434650]KTB밸류코스닥혼합형펀드,
     [00434669]KTB밸류코리아혼합형사모펀드,
     [00434678]삼성팀파워90주식형뮤추얼펀드,
     [00429658]스톰홀딩스,
     [00118831]아이넥스테크놀로지,
     [00205483]세종토건,
     [00434492]부평유선방송,
     [00435622]KTB온누리혼합형펀드,
     [00435631]미래에셋인디펜던스오십혼합형펀드,
     [00435695]KTB드림코스닥혼합형펀드,
     ...]




```python
all = dart_fss.api.filings.get_corp_code()
all
```


    Output()





    [{'corp_code': '00434003',
      'corp_name': '다코',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434456',
      'corp_name': '일산약품',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00430964',
      'corp_name': '굿앤엘에스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00432403',
      'corp_name': '한라판지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00388953',
      'corp_name': '크레디피아제이십오차유동화전문회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00179984',
      'corp_name': '연방건설산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00420143',
      'corp_name': '브룩스피알아이오토메이션잉크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00401111',
      'corp_name': '매경아이비아이',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435534',
      'corp_name': '캐드뱅크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00430186',
      'corp_name': '엠와이오피삼차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00430201',
      'corp_name': '엠와이오피이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00430210',
      'corp_name': '엠와이오피일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00430229',
      'corp_name': '포스미디어',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00140432',
      'corp_name': '축복할렐루야',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00426208',
      'corp_name': '한국전자화학',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433262',
      'corp_name': 'ConnachtCapitalMarketInvestmentLtd.',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433749',
      'corp_name': '선진아이티',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433785',
      'corp_name': '팀스코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00196079',
      'corp_name': '에넥스하이테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435048',
      'corp_name': '세이스텝바이스텝혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435057',
      'corp_name': '유리알파헷지채권혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00108843',
      'corp_name': '한기술정보통신',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00443232',
      'corp_name': '다움종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00248293',
      'corp_name': '한국애치슨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00455662',
      'corp_name': '고은상사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00149318',
      'corp_name': '조흥종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00451347',
      'corp_name': '유니즈유통',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415105',
      'corp_name': '창대화장품',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00420824',
      'corp_name': '문화종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00389439',
      'corp_name': '한국종합미디어',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00454016',
      'corp_name': '아이펜텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00452072',
      'corp_name': '대홍염공',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00437602',
      'corp_name': '지오항공여행사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00365518',
      'corp_name': '헤이아니타코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00246967',
      'corp_name': '태산산업개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00445559',
      'corp_name': '군포종합시장',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00444657',
      'corp_name': '기우',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00448936',
      'corp_name': '라시도',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00405658',
      'corp_name': '예전미디어',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00410818',
      'corp_name': '세미가',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00416061',
      'corp_name': '대닉스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00448909',
      'corp_name': '인포핸드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00445407',
      'corp_name': '지현개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421647',
      'corp_name': '한국부동산신탁제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421425',
      'corp_name': 'ISCCaymanLtd.',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00423265',
      'corp_name': '연산',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00423292',
      'corp_name': '씨케이알유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00420602',
      'corp_name': '디에스피',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00307505',
      'corp_name': 'LOMBARDKOREAILIMITED',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00218229',
      'corp_name': '승진씨앤씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00241397',
      'corp_name': '우신투자자문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421896',
      'corp_name': '외환카드제오차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00365712',
      'corp_name': '태연',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00388616',
      'corp_name': '글로벌금강제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00230407',
      'corp_name': '글로벌렌탈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00423566',
      'corp_name': '뤼미에르에셋',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00423274',
      'corp_name': '바사라엔터테인먼트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00419688',
      'corp_name': '대백유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00419712',
      'corp_name': '아이키키',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414665',
      'corp_name': '진명씨앤씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421869',
      'corp_name': '한경핫벤처',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421957',
      'corp_name': '우리부동산제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00255442',
      'corp_name': '영진상운',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427517',
      'corp_name': '한국토지신탁제오차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00376152',
      'corp_name': '다드림커뮤니케이션',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00382241',
      'corp_name': 'ARISAIGASIANSMALLCOMPANIESFUND(L)BHD',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00431501',
      'corp_name': '싱가포르개발은행서울지점',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434270',
      'corp_name': '삼성인덱스프리미엄30혼합형뮤추얼펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434289',
      'corp_name': 'KTB혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434298',
      'corp_name': 'KTB플러스찬스혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434313',
      'corp_name': 'KTB포트폴리오스타혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434322',
      'corp_name': 'KTB에버스타혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429463',
      'corp_name': '나노이앤씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429515',
      'corp_name': '지산엔터프라이즈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00432175',
      'corp_name': '유아이에스코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00387033',
      'corp_name': '트리플에스유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00384045',
      'corp_name': '크레디피아제이십일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00431608',
      'corp_name': '싱가포르개발은행',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00431705',
      'corp_name': '엘지팩토링제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00430256',
      'corp_name': '이피에스뱅크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00431167',
      'corp_name': '이라이프네트워크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00432315',
      'corp_name': '덕성',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00413134',
      'corp_name': '타오건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435376',
      'corp_name': '장원코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00110909',
      'corp_name': '대신통상',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00245995',
      'corp_name': '삼광제지공업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00220695',
      'corp_name': '서울교육',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00211794',
      'corp_name': '보성패션',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00454496',
      'corp_name': '넥스탑',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00455592',
      'corp_name': '마니빌',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00370796',
      'corp_name': '제이엘코프',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00199401',
      'corp_name': '컴마을',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00369596',
      'corp_name': '삼신크리에이션',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00210078',
      'corp_name': '호한통상',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00363398',
      'corp_name': '케이엠티',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00110042',
      'corp_name': '대백가구',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00364324',
      'corp_name': '청빛산업개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00248017',
      'corp_name': '삼양전자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00452179',
      'corp_name': '숭민코리아유통',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00413754',
      'corp_name': '유오티앤씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00343163',
      'corp_name': '한라스페코중공업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00452513',
      'corp_name': '알본',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435978',
      'corp_name': '상일디지털',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00368153',
      'corp_name': '서전어패럴',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00455149',
      'corp_name': '웰비스트랜스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00249946',
      'corp_name': '한국키엔스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00110839',
      'corp_name': '대신생명보험',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00293798',
      'corp_name': '대성메디테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00113119',
      'corp_name': '대한알루미늄공업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424389',
      'corp_name': '남성엠케이',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424486',
      'corp_name': '씨엠액텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00224734',
      'corp_name': '한국부동산신탁',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00197713',
      'corp_name': '주은산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421948',
      'corp_name': '신엘지프라이머리제이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00422381',
      'corp_name': '데코제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00350446',
      'corp_name': '뉴스테이트삼차모기지유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00396642',
      'corp_name': '엘지수퍼센터',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425449',
      'corp_name': '아이클릭세븐',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425458',
      'corp_name': '월드인코레스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425333',
      'corp_name': '코리아픽시컴',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424617',
      'corp_name': '산은부동산제사차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424006',
      'corp_name': '글로벌자이언트시스템',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424051',
      'corp_name': '신클레어',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00403599',
      'corp_name': '에이에스피기업구조조정전문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425519',
      'corp_name': 'Marubeni-ItochuSteelInc.',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00224585',
      'corp_name': '신한',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429524',
      'corp_name': '우리모아제이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429533',
      'corp_name': '글로벌사모안정혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00432722',
      'corp_name': '파워외환카드제팔차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00432786',
      'corp_name': '파워외환카드제오차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429728',
      'corp_name': '영퓨처',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00428668',
      'corp_name': '코로볼틴펀드리미티드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00430751',
      'corp_name': '대창크랑크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00385372',
      'corp_name': '허츠제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00431680',
      'corp_name': '새암교육',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00386308',
      'corp_name': '반지종합상가',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00256450',
      'corp_name': '동서산업건설(가칭)',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00290816',
      'corp_name': '대우종합기계(가칭)',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00291532',
      'corp_name': '대우조선공업(가칭)',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00127990',
      'corp_name': '삼일상호저축은행',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00431565',
      'corp_name': '케이디에스에스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00399959',
      'corp_name': '비젼케이파트너스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00430238',
      'corp_name': '리버랜드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00263034',
      'corp_name': '동양선재',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00205298',
      'corp_name': '춘천미도파',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00431042',
      'corp_name': '거버너스M&A사모펀드3호',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00348715',
      'corp_name': '아이앤비골드문브이에이치',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00447964',
      'corp_name': '체리미디어',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00448361',
      'corp_name': '경원하이텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00185851',
      'corp_name': '중원화학',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00445735',
      'corp_name': '나크나인',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00385770',
      'corp_name': '동남해상관광호텔',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00319245',
      'corp_name': '한성선박',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00126502',
      'corp_name': '삼성콘크리트공업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00363440',
      'corp_name': '엠알더블유테크노로지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00445522',
      'corp_name': '제이에이치홀딩스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00320302',
      'corp_name': '동연산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00444958',
      'corp_name': '우양주택건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00441836',
      'corp_name': '해진하우징',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00445203',
      'corp_name': '대림전자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00445629',
      'corp_name': '효헌산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00454052',
      'corp_name': '우림산업개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00454414',
      'corp_name': '에이스하이테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00196857',
      'corp_name': '해표푸드서비스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00413383',
      'corp_name': '에프씨산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00225098',
      'corp_name': '극동뉴메릭',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00410304',
      'corp_name': '서울드림랜드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00310998',
      'corp_name': '한국미라이공업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415114',
      'corp_name': '21세기화장품',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00451000',
      'corp_name': '광명산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00369985',
      'corp_name': '다음솔루션',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00199809',
      'corp_name': '이성화학',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00371670',
      'corp_name': '정우조명',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00401430',
      'corp_name': '모바일웰컴',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00247027',
      'corp_name': '푸른건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00144058',
      'corp_name': '월다크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00416867',
      'corp_name': '길도건업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00456263',
      'corp_name': '원일스포지움',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436339',
      'corp_name': '용인자원',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00120748',
      'corp_name': '마산강관',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00386724',
      'corp_name': '세창철강공업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00255390',
      'corp_name': '재무와정보',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00455547',
      'corp_name': '대양중공업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00233398',
      'corp_name': '이에이지씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00405065',
      'corp_name': '페타코페트로륨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425537',
      'corp_name': 'MarubeniCorporation',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424158',
      'corp_name': '캐피탈라인',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00100920',
      'corp_name': '건설증권',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00370167',
      'corp_name': '일진전자통신',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00409131',
      'corp_name': '오픈솔루션',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424194',
      'corp_name': 'AMERICAORIENTALGROUP',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00364713',
      'corp_name': 'mvp창업투자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00408901',
      'corp_name': '라이져',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00161170',
      'corp_name': '한라시멘트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00423557',
      'corp_name': '한국알리안츠화재해상보험',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00307444',
      'corp_name': '코리아벌처투자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00370468',
      'corp_name': '티에스케이지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424547',
      'corp_name': '메리츠투자자문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424219',
      'corp_name': '텔레닉스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424185',
      'corp_name': '유니텍워터시스템즈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424556',
      'corp_name': '거륜씨앤씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00121631',
      'corp_name': '문화',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424866',
      'corp_name': '모비도미',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424884',
      'corp_name': '에이치케이인베스트먼트유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424927',
      'corp_name': 'LiquidmetalTechnologies',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00423797',
      'corp_name': '모멘타(케이만)',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433350',
      'corp_name': 'KTB프라임8호혼합형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433369',
      'corp_name': '유리명품장기채권형사모펀드3호',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433378',
      'corp_name': '유리유니콘채권혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433387',
      'corp_name': '맥쿼리아이엠엠프라임7호채권형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433420',
      'corp_name': '마이에셋애국성장형이호펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433457',
      'corp_name': '채권플러스알파2호펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433466',
      'corp_name': '마이다스사모프라임안정형2호펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00376073',
      'corp_name': '테크포인트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00234306',
      'corp_name': '부국개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429418',
      'corp_name': '세닥에듀케이션',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429977',
      'corp_name': '에이치엘홀딩스에스에이',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00340786',
      'corp_name': '크레디리요네증권',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00218928',
      'corp_name': '케이티인더스트리',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00106793',
      'corp_name': '김천상호저축은행',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00378886',
      'corp_name': '이화홀딩스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433484',
      'corp_name': '미래에셋유니온사모혼합형펀드2호',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433493',
      'corp_name': '맥쿼리아이엠엠액티브채권형사모펀드3호',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433509',
      'corp_name': '맥쿼리아이엠엠프라임6호혼합형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433518',
      'corp_name': '유리명품장기채권형사모펀드2호',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00406596',
      'corp_name': '신우쉬핑',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00443001',
      'corp_name': '동흥컨설팅',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00363741',
      'corp_name': '디조콤',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436375',
      'corp_name': '맘모스산업개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00222277',
      'corp_name': '아성',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00446284',
      'corp_name': '디토정보기술',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00446682',
      'corp_name': '오우디앤씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00139995',
      'corp_name': '에어웨이엑스프레스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00444602',
      'corp_name': '탑월드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00446433',
      'corp_name': '옥시큐어',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00150314',
      'corp_name': '진로종합유통',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00231840',
      'corp_name': '케이에프텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00236243',
      'corp_name': '나토상사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00309479',
      'corp_name': '지오이네트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00447034',
      'corp_name': '이십일세기종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00447496',
      'corp_name': '일현건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00300928',
      'corp_name': '삼영기공',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00317566',
      'corp_name': '삼능주택',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00412001',
      'corp_name': '동해',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00155407',
      'corp_name': '풍광직물',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00443542',
      'corp_name': '기성텍스타일',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00179726',
      'corp_name': '제텍스바론',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00300982',
      'corp_name': '국제개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00298818',
      'corp_name': '유유후마킬라',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424644',
      'corp_name': '피앤씨미디어',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00350570',
      'corp_name': '비앤에프투자자문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424316',
      'corp_name': '한국부동산신탁제이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00368551',
      'corp_name': '에이텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424307',
      'corp_name': '덕경종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425078',
      'corp_name': '글로벌스페셜혼합형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00154499',
      'corp_name': '태화',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424653',
      'corp_name': '씨앤앰유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414522',
      'corp_name': '온누리방송',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425120',
      'corp_name': '케이티엠',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00356723',
      'corp_name': '아이앤비골드문컨설팅',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00375506',
      'corp_name': '동국제강제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424769',
      'corp_name': '밸류노믹스기업구조조정전문회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00223300',
      'corp_name': '조창',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00378178',
      'corp_name': '테크노켐',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00360294',
      'corp_name': '영지통상',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425209',
      'corp_name': 'RosewellConsulting&InvestmentLtd.',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433527',
      'corp_name': '유리시티즌장기채권형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433536',
      'corp_name': 'KTB장기채권형사모펀드3호',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433545',
      'corp_name': 'KTB장기채권형사모펀드4호',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433554',
      'corp_name': '맥쿼리아이엠엠포세이돈채권형사모펀드4호',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433563',
      'corp_name': '마이에셋애국안정형1호펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434702',
      'corp_name': '노보스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434711',
      'corp_name': '세이유니온채권혼합형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434720',
      'corp_name': 'LG드림혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434739',
      'corp_name': '알파그로스주식형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434748',
      'corp_name': '유리알파헷지채권혼합형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434757',
      'corp_name': '알파헷지이기욱혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434775',
      'corp_name': '맥쿼리IMM홀인원채권형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434793',
      'corp_name': '유리시장중립채권형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434809',
      'corp_name': '유리알파30채권혼합형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00432573',
      'corp_name': '파워외환카드제사차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00432607',
      'corp_name': '파워외환카드제이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00432643',
      'corp_name': '케드제이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00323390',
      'corp_name': '굿윌경영자문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00412861',
      'corp_name': '국제금속산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00443913',
      'corp_name': '덕정무역',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00315179',
      'corp_name': '삼성코닝마이크로옵틱스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00165264',
      'corp_name': '혜성건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00368171',
      'corp_name': '코스모에쿼티파트너스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00369480',
      'corp_name': '경빈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00446196',
      'corp_name': '내외시스템',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00108311',
      'corp_name': '태승어패럴',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00105615',
      'corp_name': '금동조명',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00360197',
      'corp_name': '태광정밀공업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00360364',
      'corp_name': '게르마니셀로이드코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00366720',
      'corp_name': '청우제강',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00273536',
      'corp_name': '필리아텔레콤',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00443375',
      'corp_name': '진도개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00447511',
      'corp_name': '만남과축복',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00403872',
      'corp_name': '영상산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00243793',
      'corp_name': '카이저산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00441757',
      'corp_name': '쌈솔',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00445221',
      'corp_name': '링크테크21',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00448769',
      'corp_name': '건화메디팜',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00351357',
      'corp_name': '윈윈창업투자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00371333',
      'corp_name': '지티웹코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00392716',
      'corp_name': '트랜스미디어매니지먼트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424398',
      'corp_name': '남성유통',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00380322',
      'corp_name': '무지개유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00387264',
      'corp_name': '엘지화학제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425379',
      'corp_name': '페가수스캐피탈아시아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421595',
      'corp_name': '한솔케미언스제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00128564',
      'corp_name': '삼천리M&C',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00304757',
      'corp_name': '넥스트디앤드에스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00407142',
      'corp_name': '드림라인제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00408044',
      'corp_name': '동국산업제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00112387',
      'corp_name': '휴먼이노텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00423539',
      'corp_name': '자도',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00103981',
      'corp_name': '광전자INT',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00416478',
      'corp_name': '굿케이디비제삼차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00418801',
      'corp_name': '신엑스퍼트유동화전문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00419332',
      'corp_name': '비발디제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00418078',
      'corp_name': '두산위브유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00419651',
      'corp_name': '코오롱폴리스유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00251695',
      'corp_name': '메디캐피탈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00432661',
      'corp_name': '파워외환카드제삼차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00430858',
      'corp_name': '에이치에스비프로퍼티원인베스트먼트유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00432670',
      'corp_name': '서상금속',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434827',
      'corp_name': '세이한가족주식형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434872',
      'corp_name': '알파크레디트플러스채권형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434881',
      'corp_name': '알파국공채채권형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434906',
      'corp_name': '세이에이스알파혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434915',
      'corp_name': '맥쿼리IMM코리아플러스채권형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434924',
      'corp_name': '맥쿼리IMM마켓뉴트럴혼합형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434933',
      'corp_name': '세이원채권형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435093',
      'corp_name': '그레이터차이나1호사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435109',
      'corp_name': '윌러스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00431820',
      'corp_name': '디베스트사모엠엔에이펀드일호',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00398525',
      'corp_name': '미래에셋프리미어전환혼합형이호펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00260967',
      'corp_name': '디지텔',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00378956',
      'corp_name': '유리세이프롱숏채권혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00164104',
      'corp_name': '리젠트화재보험',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00101266',
      'corp_name': '경남리스금융',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00412834',
      'corp_name': '굿머니',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00226343',
      'corp_name': '한소닉테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00150147',
      'corp_name': '지산개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00416937',
      'corp_name': '지구환경산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00132497',
      'corp_name': '성도통상',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00216461',
      'corp_name': '에프샵',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00369301',
      'corp_name': '근영전자통신',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00360106',
      'corp_name': '보해주정',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00183710',
      'corp_name': '영화',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00410483',
      'corp_name': '윈스텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00409928',
      'corp_name': '조한도시개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00209647',
      'corp_name': '대웅전기산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00370316',
      'corp_name': '해피라인',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00134246',
      'corp_name': '세원건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00444806',
      'corp_name': '린나이씨에스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00233112',
      'corp_name': '성우전자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00297758',
      'corp_name': '에스더블유씨코퍼레이션',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00450986',
      'corp_name': '미도산업개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00442206',
      'corp_name': '덕성섬유',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00361664',
      'corp_name': '기흥종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00370334',
      'corp_name': '이에이치상사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00432616',
      'corp_name': '웨이브티브이',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00444073',
      'corp_name': '축산농협안산연합사료',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00405436',
      'corp_name': '유니크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414319',
      'corp_name': '송학장갑',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00261610',
      'corp_name': '위트비전',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00362432',
      'corp_name': '월드무역',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415293',
      'corp_name': '오픈테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00413204',
      'corp_name': '아피아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00413277',
      'corp_name': '차세대정보통신',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00268455',
      'corp_name': '조흥신탁유동화전문회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00273606',
      'corp_name': '오토일천구백구십구의일유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00303369',
      'corp_name': '한국토지신탁제이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00317043',
      'corp_name': '포커스제1차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00328517',
      'corp_name': '베스트이지제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00341776',
      'corp_name': '모비스코람유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00362131',
      'corp_name': '아이에스피',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427492',
      'corp_name': '한실흥산',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00363413',
      'corp_name': '아이티엔방송',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00302829',
      'corp_name': '슈퍼데크코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00426758',
      'corp_name': '산은부동산제오차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427474',
      'corp_name': '덕화산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00428695',
      'corp_name': '국민카드이천이의일유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00366508',
      'corp_name': '마일스톤벤처투자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00402208',
      'corp_name': '에스비아이코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00175021',
      'corp_name': '씨티은행',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429250',
      'corp_name': 'AllianzFinanceB.V.',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425777',
      'corp_name': '동의보감유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00109125',
      'corp_name': '세화기술투자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00388810',
      'corp_name': '미래에셋프리미어혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00383426',
      'corp_name': '마이다스차익거래안정혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00146676',
      'corp_name': '아이씨켐',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00338152',
      'corp_name': '소프트윈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00438902',
      'corp_name': '신하나로유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00432856',
      'corp_name': '벽산건설블루밍제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00431033',
      'corp_name': '이천일아울렛제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00240866',
      'corp_name': '씨마유통',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00440934',
      'corp_name': '캠앤아이코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00440952',
      'corp_name': '제이경영컨설팅',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435905',
      'corp_name': '이리연료',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435598',
      'corp_name': '태거산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00350136',
      'corp_name': '마인드텔',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00350206',
      'corp_name': '엘파오벤쳐캐피탈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00268288',
      'corp_name': '심스밸리',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00105846',
      'corp_name': 'LGEI',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00350756',
      'corp_name': '유리크레디트회사채혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00149497',
      'corp_name': '알파캐피탈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00264778',
      'corp_name': '유니씨앤티',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00289227',
      'corp_name': '미래에셋파이오니어벤처코스닥펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00449184',
      'corp_name': '디에이치파트너스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00369028',
      'corp_name': '근하종합개발호텔엑스포',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00152491',
      'corp_name': '코락',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00445601',
      'corp_name': '터보엔지니어링',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00407610',
      'corp_name': '알파엔지니어링',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00146241',
      'corp_name': '명성건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00446071',
      'corp_name': '스카이함백',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00368384',
      'corp_name': '비에스그룹',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00446840',
      'corp_name': '삼부이엔씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00245791',
      'corp_name': '두앙종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00449625',
      'corp_name': '신성전자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00375223',
      'corp_name': '한국기업금융자문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00411631',
      'corp_name': '고룡',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00256326',
      'corp_name': '아성식품',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00367330',
      'corp_name': '세원지애에이치',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00371838',
      'corp_name': '남양주택건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00246480',
      'corp_name': '이조해운',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00359304',
      'corp_name': '한서화학',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415600',
      'corp_name': '대륭전자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00422910',
      'corp_name': '서울에프엔텍파트너스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00451055',
      'corp_name': '팔공산온천관광호텔',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00448839',
      'corp_name': '택산개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00234670',
      'corp_name': '동진피엠씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00224707',
      'corp_name': '대흥정공',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00193568',
      'corp_name': '신대광주택',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415080',
      'corp_name': '아프로시스템스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415053',
      'corp_name': '화진코스메틱',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414869',
      'corp_name': '모비야',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00365527',
      'corp_name': '우리켐테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00364245',
      'corp_name': 'ABC',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00364005',
      'corp_name': '캐피탈아거스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00413329',
      'corp_name': '유니솔',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00215222',
      'corp_name': '세화유통',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00252481',
      'corp_name': '용강',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00369897',
      'corp_name': '기바전자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00310855',
      'corp_name': '에프에스비티아이코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00370015',
      'corp_name': '디지텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00303448',
      'corp_name': '알에이코프',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00404394',
      'corp_name': '매경휴스닥',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00201946',
      'corp_name': '한국이연',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00304207',
      'corp_name': '한원텔레콤',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00305093',
      'corp_name': '진우',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00410720',
      'corp_name': '탑종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00354354',
      'corp_name': '썬키스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00311049',
      'corp_name': '위슬런',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00412782',
      'corp_name': '대산반도체',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00426615',
      'corp_name': '네오소프트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00164061',
      'corp_name': '드림에스디',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00381659',
      'corp_name': '크레디피아제십구차유동화전문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00382959',
      'corp_name': '콩코드캐피탈아시아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00118886',
      'corp_name': '에이브이씨닷컴',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00374835',
      'corp_name': '케이씨알파트너스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00115700',
      'corp_name': '동성투자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00389192',
      'corp_name': '오엔씨네트웍스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00346452',
      'corp_name': '씨에스지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00420356',
      'corp_name': '하이페리온제이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425528',
      'corp_name': '부산유조선',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427784',
      'corp_name': '목동우림루미아트유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00244297',
      'corp_name': '천보파이낸스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00428817',
      'corp_name': '나라펫',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425740',
      'corp_name': '하이케어시스템즈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00389086',
      'corp_name': '우리금융제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425759',
      'corp_name': '키치녹스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00426721',
      'corp_name': '에이치에스제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00426651',
      'corp_name': '신드림풀유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427951',
      'corp_name': '넥센캐피탈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00448112',
      'corp_name': '종연산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00446655',
      'corp_name': '성환',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00357111',
      'corp_name': '삼두디엔에스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00360717',
      'corp_name': '녹십자피디',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00411321',
      'corp_name': '율비',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00193221',
      'corp_name': '삼희산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00407595',
      'corp_name': '아이스타뮤직',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00147417',
      'corp_name': '전일제지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00367075',
      'corp_name': '신흥울테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00448501',
      'corp_name': '삼양이컴',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00197856',
      'corp_name': '전주코아호텔',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00378017',
      'corp_name': '헬리오스기업구조조정전문회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00207384',
      'corp_name': '동일상사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00233927',
      'corp_name': '헨켈코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00255372',
      'corp_name': '센텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00246693',
      'corp_name': '태흥기업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00367932',
      'corp_name': '만적',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00334341',
      'corp_name': '성신무역',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00190224',
      'corp_name': '새한철강',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00448291',
      'corp_name': '한림종합개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00445391',
      'corp_name': '동방귀석',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00169321',
      'corp_name': '부곡관광',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434076',
      'corp_name': '에이취.엠.에스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00205128',
      'corp_name': '서통테크놀로지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00450250',
      'corp_name': '한경섬유',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00368126',
      'corp_name': '세진티앤엠',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00175386',
      'corp_name': '경기교통',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00205748',
      'corp_name': '강호개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00358378',
      'corp_name': '만덕',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00221409',
      'corp_name': '한국어센셜소프트웨어',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414328',
      'corp_name': '와우북',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00188061',
      'corp_name': '한서시계',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00409982',
      'corp_name': '부풍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00134149',
      'corp_name': '세우무역',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414461',
      'corp_name': '신우종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00304508',
      'corp_name': '중원',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00247753',
      'corp_name': '아스트로',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00368816',
      'corp_name': '한국멀티넷',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00366085',
      'corp_name': '넥스트미디어아이',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00412302',
      'corp_name': '일성리조트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00387246',
      'corp_name': '동광산건',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00265050',
      'corp_name': '유렉셀테크놀러지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00236182',
      'corp_name': '성일컴퓨텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00296555',
      'corp_name': '엠에프씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00327226',
      'corp_name': '얼라이언스시스템',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00412852',
      'corp_name': '대한주택이앤지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00143970',
      'corp_name': '원창판지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00301404',
      'corp_name': '한국피시',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00109541',
      'corp_name': '대륙공업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00404880',
      'corp_name': '디지털테크놀러지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00393858',
      'corp_name': '드림데이타',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00385123',
      'corp_name': '리첸시아유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429010',
      'corp_name': '코리아페이넷',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424963',
      'corp_name': '디더블유씨유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425768',
      'corp_name': '티지일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00426749',
      'corp_name': '피앤지정보통신',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00330415',
      'corp_name': '인바인',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00150794',
      'corp_name': '진흥주택',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429038',
      'corp_name': '굿앤세이프',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421081',
      'corp_name': '디바이너',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00361734',
      'corp_name': '케이아이티창업투자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00388768',
      'corp_name': '외환카드제사차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425421',
      'corp_name': '오프마이십일',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421850',
      'corp_name': '창신테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425315',
      'corp_name': '파워엑시스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427580',
      'corp_name': '삼성프론티어제십이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425218',
      'corp_name': '쓰리엔제이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00106951',
      'corp_name': '낙산관광호텔',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00395661',
      'corp_name': '현지개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00275118',
      'corp_name': '케이티비벤처벌처일호펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00295389',
      'corp_name': '메타텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00389147',
      'corp_name': '골든보우창업투자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00126803',
      'corp_name': '삼아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00242341',
      'corp_name': '에스엠아이씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00440314',
      'corp_name': '오토피아제팔차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00440332',
      'corp_name': '니즈솔루션',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00441322',
      'corp_name': '이나라카드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00440165',
      'corp_name': '히타치전선',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00288884',
      'corp_name': '미래에셋드림파이오니어펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00148452',
      'corp_name': 'GPS',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00156017',
      'corp_name': '하나은행',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00261045',
      'corp_name': '시스컴',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00437532',
      'corp_name': '개풍주택개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00303095',
      'corp_name': '지오스테크널러지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00438753',
      'corp_name': 'IndusAsiaPacificFund,Ltd.',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00367464',
      'corp_name': '지앤텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00201955',
      'corp_name': '금화냉동',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00409849',
      'corp_name': '혜성',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00131443',
      'corp_name': '서통상사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00174022',
      'corp_name': '유창섬유',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00444763',
      'corp_name': '피프',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00412171',
      'corp_name': '모수인터내쇼날',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00232973',
      'corp_name': '동해산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00152419',
      'corp_name': '대농중공업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00257413',
      'corp_name': '신영팩토링',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00362511',
      'corp_name': '승진건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00446743',
      'corp_name': '아워스인베스트먼트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00253055',
      'corp_name': '태흥산업개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00448714',
      'corp_name': '마하인더스트리',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00448705',
      'corp_name': '모아건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00101716',
      'corp_name': '경북레미콘',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00447876',
      'corp_name': '그루빅',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00448671',
      'corp_name': '라이프건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00217150',
      'corp_name': '대진종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00164344',
      'corp_name': '해피아이',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00303314',
      'corp_name': '성서',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00451213',
      'corp_name': '한신공업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00407416',
      'corp_name': '오랙스정유',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00178675',
      'corp_name': '이논',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00367181',
      'corp_name': '예들',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00439062',
      'corp_name': '세제',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00413514',
      'corp_name': '가인수산',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00127538',
      'corp_name': '삼원산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00370051',
      'corp_name': '유덕건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415123',
      'corp_name': '크로스전자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00106012',
      'corp_name': '금성텔',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00158495',
      'corp_name': '한국아프라이드매그네틱스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00299774',
      'corp_name': '스타럽스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414911',
      'corp_name': '텔레프리',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414762',
      'corp_name': '금화도시개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00234078',
      'corp_name': '길정종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00412515',
      'corp_name': '메디링스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00151076',
      'corp_name': '창원개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00170512',
      'corp_name': '우신레저산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00370033',
      'corp_name': '연이산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00406587',
      'corp_name': '다른신문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00413471',
      'corp_name': '비투올네트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00248804',
      'corp_name': '성진사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00359854',
      'corp_name': '네투스테크놀러지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00252870',
      'corp_name': '동구',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00300432',
      'corp_name': '비아이캐피탈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415938',
      'corp_name': '세아개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00370714',
      'corp_name': '퍼시픽스타',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00345693',
      'corp_name': 'SKIMT',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00426226',
      'corp_name': '일신제약',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00426235',
      'corp_name': '모아에셋',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00376505',
      'corp_name': '그린페이퍼텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427058',
      'corp_name': '원업제이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427100',
      'corp_name': '두손테크피아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427331',
      'corp_name': '유니맥코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429144',
      'corp_name': '아하크레딧유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429180',
      'corp_name': '거버너스M&A사모펀드2호',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00419916',
      'corp_name': '기가솔',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421009',
      'corp_name': '모쿠스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00363796',
      'corp_name': '남양산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00302148',
      'corp_name': '에이팩스기술투자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00426314',
      'corp_name': '에스지테크놀러지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427146',
      'corp_name': '도이체방크아게런던',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00245065',
      'corp_name': '에이에스엠엘에스씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427182',
      'corp_name': '얼라이언스캐피탈파트너즈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00382852',
      'corp_name': '대진산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00362113',
      'corp_name': '하늘사랑',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00220756',
      'corp_name': '씨앤씨캐피탈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00162319',
      'corp_name': '한양상사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00355511',
      'corp_name': 'Photronics,Inc.',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00400176',
      'corp_name': '무빙넷',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00396402',
      'corp_name': '슈마커코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00439938',
      'corp_name': '유케이',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00337977',
      'corp_name': '캐피탈리서치앤매니지먼트컴퍼니',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436047',
      'corp_name': '월드타운',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00387097',
      'corp_name': '센텀파크유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00274410',
      'corp_name': '인트빔',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00328100',
      'corp_name': '나래소프트시스템',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00243845',
      'corp_name': '삼광고하켐',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00336260',
      'corp_name': 'OAKMARKINTERNATIONALFUND',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00262026',
      'corp_name': '신중앙99-1유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00264431',
      'corp_name': '크레디피아유동화전문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00264495',
      'corp_name': '중소기업유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00267067',
      'corp_name': '산은캐피탈제일호유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00290791',
      'corp_name': '국민제이차유동화전문회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00297837',
      'corp_name': '국민제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429162',
      'corp_name': '남양씨앤씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00203643',
      'corp_name': '유일냉장',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00450108',
      'corp_name': '평산공영',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00171414',
      'corp_name': '파산자한국산업증권',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00200549',
      'corp_name': '대홍방직',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00114543',
      'corp_name': '도투락',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00197607',
      'corp_name': '해덕기업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00258263',
      'corp_name': '이수금속',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00363617',
      'corp_name': '세미코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00450287',
      'corp_name': '정방종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00413082',
      'corp_name': '성우종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00449537',
      'corp_name': '신아토건',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00163071',
      'corp_name': '한일염공',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00453239',
      'corp_name': '코스모건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414267',
      'corp_name': '한국방송출판',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00349088',
      'corp_name': '태성개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00451514',
      'corp_name': '월성주택건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00386830',
      'corp_name': '심도산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00410128',
      'corp_name': '코리아라이닝',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00161198',
      'corp_name': '한라종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00126849',
      'corp_name': '삼안공영',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00437824',
      'corp_name': '제석주택',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00363176',
      'corp_name': '한국모빌솔루션',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00299871',
      'corp_name': '연화상사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00336686',
      'corp_name': '현대티타늄',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00340892',
      'corp_name': '한강온천',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415725',
      'corp_name': '나우아이엔에스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00306205',
      'corp_name': '디아이씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00371351',
      'corp_name': '비앤에스아이엔씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00369851',
      'corp_name': '창원건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415840',
      'corp_name': '알루테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00246666',
      'corp_name': '대상하이디어',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00153296',
      'corp_name': '태강산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00161268',
      'corp_name': '한륙전자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00210476',
      'corp_name': '영신산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00365581',
      'corp_name': '이사이트랩',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00183598',
      'corp_name': '영신플랜트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00417088',
      'corp_name': '정연산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415062',
      'corp_name': '아코텔레콤',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00172529',
      'corp_name': '대영',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00407337',
      'corp_name': '프라임플러스캐피탈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00405092',
      'corp_name': '에스티지시큐리티',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00226060',
      'corp_name': '보성설비',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00206349',
      'corp_name': '록정개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00217035',
      'corp_name': '신아스포츠',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00224318',
      'corp_name': '뉴라인여신금융',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424945',
      'corp_name': '중소기업제삼차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00428604',
      'corp_name': '알비에이',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00424565',
      'corp_name': '체리스톤코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00226574',
      'corp_name': '세모화학',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425157',
      'corp_name': '리딩씨앤씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427340',
      'corp_name': '폴리코',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427429',
      'corp_name': '산은굿밸류제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00420453',
      'corp_name': '이프리즘',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00403696',
      'corp_name': '디미디어',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00417592',
      'corp_name': '유피텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00365998',
      'corp_name': '티브이가이드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00412913',
      'corp_name': '스타코리아웹케스팅',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421355',
      'corp_name': '아라정보기술',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00426439',
      'corp_name': '코리아컨텐츠네트워크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427386',
      'corp_name': '티티월드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00167129',
      'corp_name': '흥산건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00217707',
      'corp_name': '연덕건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00426518',
      'corp_name': '비추미코리아제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00426536',
      'corp_name': '크레디피아제삼십오차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00426545',
      'corp_name': '아하론제삼차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00335951',
      'corp_name': '동원제일차유동화전문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436588',
      'corp_name': '케이투이',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435349',
      'corp_name': '지영상사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00331450',
      'corp_name': '아주의대벤처메딕스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00341952',
      'corp_name': '엑스퍼트유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00342739',
      'corp_name': '마이에셋유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00342988',
      'corp_name': '한아름제2차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436241',
      'corp_name': '에셋외환카드제이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436269',
      'corp_name': '에셋외환카드제육차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436296',
      'corp_name': '타이거유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00237491',
      'corp_name': '서한전자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00118099',
      'corp_name': '동원직물',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436685',
      'corp_name': '청유',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00437107',
      'corp_name': '서울전산',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436490',
      'corp_name': '씨에스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436524',
      'corp_name': '선암건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435923',
      'corp_name': '아세텔레콤',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00437541',
      'corp_name': '우리엘비제칠차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00437569',
      'corp_name': '지오택드레인',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00336385',
      'corp_name': '몬덱스코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00198253',
      'corp_name': '서광티앤씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00354062',
      'corp_name': '로직스컴퓨터',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00311818',
      'corp_name': 'RedTulipInvestments',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00452267',
      'corp_name': '아이산업개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00446141',
      'corp_name': '비코레트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00245117',
      'corp_name': '강남산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00451365',
      'corp_name': '우림엔지니어링건축사사무소',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00263627',
      'corp_name': '백현건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00413912',
      'corp_name': '우연종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00362618',
      'corp_name': '용성조선',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00202404',
      'corp_name': '송원자동차조명',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00450773',
      'corp_name': '태산종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00252852',
      'corp_name': '근도물산',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00451879',
      'corp_name': '씨에스피산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00181217',
      'corp_name': '삼흥판지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00375728',
      'corp_name': '인터내셔날쥬피텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00445823',
      'corp_name': '대륙종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00387167',
      'corp_name': '마시나코아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00256885',
      'corp_name': '부천산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00452674',
      'corp_name': '바롬테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00449421',
      'corp_name': '대방종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00209230',
      'corp_name': '영도섬유',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00412311',
      'corp_name': '미디어파트너스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00233741',
      'corp_name': '한이해운',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00299400',
      'corp_name': '금영',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00112518',
      'corp_name': '대준섬유',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00416760',
      'corp_name': '두일',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00397438',
      'corp_name': '벽송종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00198615',
      'corp_name': '평해건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00363228',
      'corp_name': '대동제지공업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415257',
      'corp_name': '동서디엔씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00369365',
      'corp_name': '케미스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00405126',
      'corp_name': '텔리맨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415266',
      'corp_name': '과일나라',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00361354',
      'corp_name': '넷츠고',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415275',
      'corp_name': '동승건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00367446',
      'corp_name': '주영크리에이션',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415673',
      'corp_name': '태광엔터프라이즈',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00171751',
      'corp_name': '한주종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00416797',
      'corp_name': '유정건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00193407',
      'corp_name': '세광종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00365943',
      'corp_name': '금양레포츠',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00363060',
      'corp_name': '게임벤처',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00418892',
      'corp_name': '마이애셋사모M&A펀드B호',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00418917',
      'corp_name': '하나로밀레니엄',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00417370',
      'corp_name': '메트로에이전시',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427508',
      'corp_name': '국민카드제십차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00367987',
      'corp_name': '시봉전자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00428020',
      'corp_name': '두산스피리츠',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00382296',
      'corp_name': '게토코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00297332',
      'corp_name': 'AmkorTechnology,Inc.',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00378929',
      'corp_name': '에이피엠쇼핑몰',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00384735',
      'corp_name': '코텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00303572',
      'corp_name': '아이거넷',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00399250',
      'corp_name': '도원닷컴',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434951',
      'corp_name': '맥쿼리장기채권형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434988',
      'corp_name': '세이리딩스톡혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434997',
      'corp_name': '세이고배당장기증권저축펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435002',
      'corp_name': '세이고배당주식형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435136',
      'corp_name': '맥쿼리IMM슈페리어채권형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434331',
      'corp_name': 'KTB채권형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434359',
      'corp_name': '글로벌퍼펙트혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434377',
      'corp_name': '삼성중소형알짜주식형뮤추얼펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434386',
      'corp_name': 'KTB장기증권저축펀드1호',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434438',
      'corp_name': 'KTB에이플러스2호혼합형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00286877',
      'corp_name': '비비앤씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436913',
      'corp_name': '대청산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436366',
      'corp_name': '링컨아카데미',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00369116',
      'corp_name': '디아이컨설팅',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00261577',
      'corp_name': '네띠앙',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434261',
      'corp_name': '크레디피아제삼십팔차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00222204',
      'corp_name': '산내들축산',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436153',
      'corp_name': '거장주택건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00437967',
      'corp_name': '쓰리디컴넷',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435914',
      'corp_name': '대양식품',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435899',
      'corp_name': '태강건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00437383',
      'corp_name': '국제전자정밀',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00351825',
      'corp_name': '투어토털닷컴',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415008',
      'corp_name': '드림미르',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436968',
      'corp_name': '부광',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436852',
      'corp_name': '도원건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436393',
      'corp_name': '현우유통',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00261142',
      'corp_name': '엘리온정보기술',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00439406',
      'corp_name': '지석공영',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421559',
      'corp_name': '에쓰엠제일차자산유동화전문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00387060',
      'corp_name': '뉴밀레니엄코람제이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434067',
      'corp_name': '렉스상사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00446938',
      'corp_name': '보나뱅크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00413161',
      'corp_name': '토탈메드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00450409',
      'corp_name': '엔트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00430283',
      'corp_name': '협성염공',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00370875',
      'corp_name': '디비엔지니어링',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00230878',
      'corp_name': '삼양텍스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00409867',
      'corp_name': '얄개네트워크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00385044',
      'corp_name': '지트랜코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00173245',
      'corp_name': '삼보',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00423812',
      'corp_name': '국민카드제구차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00425661',
      'corp_name': '국민카드제십일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00273907',
      'corp_name': '하나로제4차유동화전문회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00283533',
      'corp_name': '와이디세이프유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00445966',
      'corp_name': '늘푸른마을',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00450001',
      'corp_name': '이노크래프트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00449555',
      'corp_name': '강동종합유선방송',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00452443',
      'corp_name': '한림하우징',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00366836',
      'corp_name': '아이티엠',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00444426',
      'corp_name': '코산아이엔티',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00261665',
      'corp_name': '미광핸드백',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00363945',
      'corp_name': '신정건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414832',
      'corp_name': '코이넬',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00383161',
      'corp_name': '서울제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00163026',
      'corp_name': '이지닷컴',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414610',
      'corp_name': '지에프엠에스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415947',
      'corp_name': '언아더월드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00304605',
      'corp_name': '로티스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414957',
      'corp_name': '이파워게이트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00416229',
      'corp_name': '윤진개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00120243',
      'corp_name': '레이디',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00411659',
      'corp_name': '미트마트옥션',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00198314',
      'corp_name': '아싸',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00413408',
      'corp_name': '웰리치개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00163965',
      'corp_name': '항도종합금융',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00416724',
      'corp_name': '아이텍테크널러지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00218502',
      'corp_name': '중앙제약',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00364175',
      'corp_name': '우남산업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00417422',
      'corp_name': '윈로지스뉴톤보레알',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00417981',
      'corp_name': '한국지방재정공제회',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00307046',
      'corp_name': '창도건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00237349',
      'corp_name': '부국개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414364',
      'corp_name': '유경엔지니어링',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00417626',
      'corp_name': '한국레이저영상',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414337',
      'corp_name': '뷰텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00418050',
      'corp_name': '씨에이블',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415567',
      'corp_name': '아토메가',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00247984',
      'corp_name': '도레미농산',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00371494',
      'corp_name': '다인개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00358147',
      'corp_name': '호만기업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00150554',
      'corp_name': '갑을개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00305279',
      'corp_name': '에버그린유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00386326',
      'corp_name': '맥트랜스인터내셔날',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00100753',
      'corp_name': '거봉',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00204703',
      'corp_name': '대산레미콘',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00417316',
      'corp_name': '크레딧크리에이터이천이유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00207959',
      'corp_name': '신택',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00411109',
      'corp_name': '바티오테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00417477',
      'corp_name': '하우징그룹우신',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414054',
      'corp_name': '통인물류정보통신',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00303730',
      'corp_name': '에스지에스컨테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00362229',
      'corp_name': '광호',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00317326',
      'corp_name': '펜다하우스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00418430',
      'corp_name': '프르덴셜어슈어런스컴퍼니리티니드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434447',
      'corp_name': 'KTB장기증권저축펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434517',
      'corp_name': '삼성인덱스프리미엄주식형뮤추얼펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434526',
      'corp_name': 'KTB하이스타혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00433721',
      'corp_name': '한국광학초자',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434207',
      'corp_name': '광평개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434562',
      'corp_name': 'KTB밸류스타혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434571',
      'corp_name': 'KTB글로벌스타주식형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434580',
      'corp_name': 'KTB프라임4호주식형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434599',
      'corp_name': 'KTB베스트바이혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434605',
      'corp_name': 'KTB하이턴펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434614',
      'corp_name': '마이다스A등급채권혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435145',
      'corp_name': '맥쿼리아이엠엠프라임3혼합형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00396448',
      'corp_name': '피이아이코리아사모엠엔에이일호펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00430937',
      'corp_name': '아담소프트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00423034',
      'corp_name': '피델리티펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435127',
      'corp_name': '유리크레디트채권혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434544',
      'corp_name': 'KTB프리미엄찬스혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434553',
      'corp_name': 'KTB에이스찬스혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00432050',
      'corp_name': '다린정보',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00344843',
      'corp_name': '기보캐피탈제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00371908',
      'corp_name': '엘에스에프프로퍼티투유동화전문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00339090',
      'corp_name': '온디지털테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00337986',
      'corp_name': '캐피탈그룹인터내셔널인코포레이티드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00206136',
      'corp_name': '세림아이텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00440411',
      'corp_name': '코스유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00422309',
      'corp_name': '뉴밀레니엄하나유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00439257',
      'corp_name': '동양정보통신M&A',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00439284',
      'corp_name': '하이페리온제삼차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00439424',
      'corp_name': '코머스에셋',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435011',
      'corp_name': '경동실업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00428525',
      'corp_name': '에스티엑스제이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427128',
      'corp_name': '오일뱅크제삼차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00428677',
      'corp_name': '케이지브이제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436560',
      'corp_name': '인성어패럴',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00440697',
      'corp_name': '소프티안',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00439734',
      'corp_name': '동양알미늄',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00327387',
      'corp_name': '소모페스트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00437611',
      'corp_name': '젤존항공여행사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00321064',
      'corp_name': '바이오엔비텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00362557',
      'corp_name': '세원반도체',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00224105',
      'corp_name': '두원그린피아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00447654',
      'corp_name': '미도핸드백',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00453169',
      'corp_name': '대영테크',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00371388',
      'corp_name': '아이비젠',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00144340',
      'corp_name': '한화포리마',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00437204',
      'corp_name': '신케이에스유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00443302',
      'corp_name': '프라임유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436463',
      'corp_name': '우영제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00452692',
      'corp_name': '한컴리눅스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00441739',
      'corp_name': '두산건설제육유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00441669',
      'corp_name': '산은부동산제팔차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436940',
      'corp_name': '오토피아제칠차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00436959',
      'corp_name': '외환카드제팔차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00427526',
      'corp_name': '삼성신한아하론일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00264705',
      'corp_name': '현대유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00387714',
      'corp_name': '칼제일차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00300946',
      'corp_name': '백두건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00402086',
      'corp_name': '리엔텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00452461',
      'corp_name': '대양건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00100948',
      'corp_name': '건양콘크리트',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00365572',
      'corp_name': '맥스미디어',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00400486',
      'corp_name': '루넷',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00417909',
      'corp_name': '충일아스콘',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00153816',
      'corp_name': '태양연와공업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00414586',
      'corp_name': '제동',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00187637',
      'corp_name': '농협축산유통',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415035',
      'corp_name': '동서D&S',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00235864',
      'corp_name': '에스앤제이',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00416043',
      'corp_name': '창영물산',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00174280',
      'corp_name': '태화건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00417352',
      'corp_name': '동방코리아',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00238223',
      'corp_name': '영텍스타일',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00248530',
      'corp_name': '미진시스템',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00234740',
      'corp_name': '고려소재개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00417565',
      'corp_name': '아이앤알코리아기업구조조정전문',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00192958',
      'corp_name': '건륭실업',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00387459',
      'corp_name': '충주공용버스터미널',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00415761',
      'corp_name': '푸른도시개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00404011',
      'corp_name': '로고스이넷',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00168553',
      'corp_name': '대광종합건설',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00309804',
      'corp_name': '굿윌씨앤아이',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00408600',
      'corp_name': '아라아이디시',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00418731',
      'corp_name': '디엠아이디',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00363121',
      'corp_name': '웅보개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00230577',
      'corp_name': '광복산업개발',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00295671',
      'corp_name': '리빙티브이',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00418759',
      'corp_name': '산은부동산제삼차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00211448',
      'corp_name': '신라',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00406170',
      'corp_name': '글로만',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00301060',
      'corp_name': '서림개스실린더',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00242350',
      'corp_name': '파인에셋홀딩스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00134352',
      'corp_name': '세일',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00420569',
      'corp_name': '한일밀라노.존',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00422141',
      'corp_name': '첼린저이차유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00422178',
      'corp_name': '휴민텍',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00419891',
      'corp_name': '템플턴스트래티직이머징마켓츠펀드엘디씨',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00419907',
      'corp_name': '신한파이낸스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00310989',
      'corp_name': '코오롱모터스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00420976',
      'corp_name': '큐마트솔루션',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421072',
      'corp_name': '나은미디어',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00423706',
      'corp_name': 'BystronicLaserAG',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00384425',
      'corp_name': '코브코유동화전문유한회사',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00350297',
      'corp_name': '칼스버그에이에스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00421124',
      'corp_name': '아이엠씨마케팅',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434632',
      'corp_name': '글로벌채권프리미엄혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434650',
      'corp_name': 'KTB밸류코스닥혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434669',
      'corp_name': 'KTB밸류코리아혼합형사모펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434678',
      'corp_name': '삼성팀파워90주식형뮤추얼펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00429658',
      'corp_name': '스톰홀딩스',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00118831',
      'corp_name': '아이넥스테크놀로지',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00205483',
      'corp_name': '세종토건',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00434492',
      'corp_name': '부평유선방송',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435622',
      'corp_name': 'KTB온누리혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435631',
      'corp_name': '미래에셋인디펜던스오십혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     {'corp_code': '00435695',
      'corp_name': 'KTB드림코스닥혼합형펀드',
      'stock_code': None,
      'modify_date': '20170630'},
     ...]




```python
df = pd.DataFrame(all)
df

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>stock_code</th>
      <th>modify_date</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>00434003</td>
      <td>다코</td>
      <td>None</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>1</th>
      <td>00434456</td>
      <td>일산약품</td>
      <td>None</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>2</th>
      <td>00430964</td>
      <td>굿앤엘에스</td>
      <td>None</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>3</th>
      <td>00432403</td>
      <td>한라판지</td>
      <td>None</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>4</th>
      <td>00388953</td>
      <td>크레디피아제이십오차유동화전문회사</td>
      <td>None</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>103534</th>
      <td>00646510</td>
      <td>미래에셋파트너스사호사모투자전문회사</td>
      <td>None</td>
      <td>20230228</td>
    </tr>
    <tr>
      <th>103535</th>
      <td>01184822</td>
      <td>미래에셋파트너스9호사모투자</td>
      <td>None</td>
      <td>20230228</td>
    </tr>
    <tr>
      <th>103536</th>
      <td>00755252</td>
      <td>시니안</td>
      <td>None</td>
      <td>20230228</td>
    </tr>
    <tr>
      <th>103537</th>
      <td>00227582</td>
      <td>청호나이스</td>
      <td>None</td>
      <td>20230228</td>
    </tr>
    <tr>
      <th>103538</th>
      <td>01615845</td>
      <td>메타버스월드</td>
      <td>None</td>
      <td>20230228</td>
    </tr>
  </tbody>
</table>
<p>103539 rows × 4 columns</p>
</div>




```python
df_listed = df[df['stock_code'].notnull()]
```


```python
df=pd.DataFrame(all)

df_listed = df[df['stock_code'].notnull()]
df_listed.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>stock_code</th>
      <th>modify_date</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2006</th>
      <td>00260985</td>
      <td>한빛네트</td>
      <td>036720</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>2018</th>
      <td>00264529</td>
      <td>엔플렉스</td>
      <td>040130</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>2019</th>
      <td>00358545</td>
      <td>동서정보기술</td>
      <td>055000</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>2781</th>
      <td>00231567</td>
      <td>애드모바일</td>
      <td>032600</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>3884</th>
      <td>00247939</td>
      <td>씨모스</td>
      <td>037600</td>
      <td>20170630</td>
    </tr>
  </tbody>
</table>
</div>




```python
df_listed.count()
```




    corp_code      3663
    corp_name      3663
    stock_code     3663
    modify_date    3663
    dtype: int64



비상장사 **리스트**


```python
df_non_listed = df[df['stock_code'].isnull()]
```


```python
df = pd.DataFrame(all)

df_listed = df[df['stock_code'].notnull()]
df_non_listed = df[df['stock_code'].isnull()]
df_non_listed.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>stock_code</th>
      <th>modify_date</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>00434003</td>
      <td>다코</td>
      <td>None</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>1</th>
      <td>00434456</td>
      <td>일산약품</td>
      <td>None</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>2</th>
      <td>00430964</td>
      <td>굿앤엘에스</td>
      <td>None</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>3</th>
      <td>00432403</td>
      <td>한라판지</td>
      <td>None</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>4</th>
      <td>00388953</td>
      <td>크레디피아제이십오차유동화전문회사</td>
      <td>None</td>
      <td>20170630</td>
    </tr>
  </tbody>
</table>
</div>



비상장사 리스트 숫자 세어보기


```python
df = pd.DataFrame(all)

df_listed = df[df['stock_code'].notnull()]
df_non_listed = df[df['stock_code'].isnull()]
df_non_listed.count()
```




    corp_code      99876
    corp_name      99876
    stock_code         0
    modify_date    99876
    dtype: int64



엑셀로 저정해 두기


```python
df_listed.to_excel('상장종목.xlsx')
df_non_listed.to_excel('비상장종목.xlsx')
```


```python

```


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
corp_code
```




    '00126380'




```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
dart_fss.api.filings.get_corp_info(corp_code)
```




    {'status': '000',
     'message': '정상',
     'corp_code': '00126380',
     'corp_name': '삼성전자(주)',
     'corp_name_eng': 'SAMSUNG ELECTRONICS CO,.LTD',
     'stock_name': '삼성전자',
     'stock_code': '005930',
     'ceo_nm': '한종희, 경계현',
     'corp_cls': 'Y',
     'jurir_no': '1301110006246',
     'bizr_no': '1248100998',
     'adres': '경기도 수원시 영통구  삼성로 129 (매탄동)',
     'hm_url': 'www.samsung.com/sec',
     'ir_url': '',
     'phn_no': '02-2255-0114',
     'fax_no': '031-200-7538',
     'induty_code': '264',
     'est_dt': '19690113',
     'acc_mt': '12'}



증자(감자)현황


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.info.unrst_exctv_mendng_sttus(corp_code, '2021', '11011')
pd.DataFrame(data['list'])
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>corp_cls</th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>se</th>
      <th>fyer_salary_totamt</th>
      <th>jan_salary_am</th>
      <th>nmpr</th>
      <th>rm</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>미등기임원</td>
      <td>717,856,000,000</td>
      <td>790,000,000</td>
      <td>933</td>
      <td>-</td>
    </tr>
  </tbody>
</table>
</div>



- 배당 현황


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.info.alot_matter(corp_code, '2021', '11011')
pd.DataFrame(data['list'])
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>corp_cls</th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>se</th>
      <th>thstrm</th>
      <th>frmtrm</th>
      <th>lwfr</th>
      <th>stock_knd</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>주당액면가액(원)</td>
      <td>100</td>
      <td>100</td>
      <td>100</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>(연결)당기순이익(백만원)</td>
      <td>39,243,791</td>
      <td>26,090,846</td>
      <td>21,505,054</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>(별도)당기순이익(백만원)</td>
      <td>30,970,954</td>
      <td>15,615,018</td>
      <td>15,353,323</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>(연결)주당순이익(원)</td>
      <td>5,777</td>
      <td>3,841</td>
      <td>3,166</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>현금배당금총액(백만원)</td>
      <td>9,809,438</td>
      <td>20,338,075</td>
      <td>9,619,243</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>5</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>주식배당금총액(백만원)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>6</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>(연결)현금배당성향(%)</td>
      <td>25.00</td>
      <td>78.00</td>
      <td>44.70</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>7</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>현금배당수익률(%)</td>
      <td>1.80</td>
      <td>4.00</td>
      <td>2.60</td>
      <td>보통주</td>
    </tr>
    <tr>
      <th>8</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>현금배당수익률(%)</td>
      <td>2.00</td>
      <td>4.20</td>
      <td>3.10</td>
      <td>우선주</td>
    </tr>
    <tr>
      <th>9</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>주식배당수익률(%)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>보통주</td>
    </tr>
    <tr>
      <th>10</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>주식배당수익률(%)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>우선주</td>
    </tr>
    <tr>
      <th>11</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>주당 현금배당금(원)</td>
      <td>1,444</td>
      <td>2,994</td>
      <td>1,416</td>
      <td>보통주</td>
    </tr>
    <tr>
      <th>12</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>주당 현금배당금(원)</td>
      <td>1,445</td>
      <td>2,995</td>
      <td>1,417</td>
      <td>우선주</td>
    </tr>
    <tr>
      <th>13</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>주당 주식배당(주)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>보통주</td>
    </tr>
    <tr>
      <th>14</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>주당 주식배당(주)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>우선주</td>
    </tr>
  </tbody>
</table>
</div>



최대주주 현황


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.info.hyslr_sttus(corp_code, '2021', '11011')
pd.DataFrame(data['list'])
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>corp_cls</th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>stock_knd</th>
      <th>nm</th>
      <th>relate</th>
      <th>bsis_posesn_stock_co</th>
      <th>bsis_posesn_stock_qota_rt</th>
      <th>trmend_posesn_stock_co</th>
      <th>trmend_posesn_stock_qota_rt</th>
      <th>rm</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>이건희</td>
      <td>-</td>
      <td>249,273,200</td>
      <td>4.18</td>
      <td>0</td>
      <td>0.00</td>
      <td>피상속</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>삼성문화재단</td>
      <td>출연 재단</td>
      <td>1,880,750</td>
      <td>0.03</td>
      <td>1,880,750</td>
      <td>0.03</td>
      <td>-</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>홍라희</td>
      <td>최대주주의 특수관계인</td>
      <td>54,153,600</td>
      <td>0.91</td>
      <td>137,244,666</td>
      <td>2.30</td>
      <td>상속</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>우선주</td>
      <td>홍라희</td>
      <td>최대주주의 특수관계인</td>
      <td>0</td>
      <td>0.00</td>
      <td>206,633</td>
      <td>0.03</td>
      <td>상속</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>이재용</td>
      <td>최대주주의 특수관계인</td>
      <td>42,020,150</td>
      <td>0.70</td>
      <td>97,414,196</td>
      <td>1.63</td>
      <td>상속</td>
    </tr>
    <tr>
      <th>5</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>우선주</td>
      <td>이재용</td>
      <td>최대주주의 특수관계인</td>
      <td>0</td>
      <td>0.00</td>
      <td>137,757</td>
      <td>0.02</td>
      <td>상속</td>
    </tr>
    <tr>
      <th>6</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>이부진</td>
      <td>계열회사 임원</td>
      <td>0</td>
      <td>0.00</td>
      <td>55,394,044</td>
      <td>0.93</td>
      <td>상속</td>
    </tr>
    <tr>
      <th>7</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>우선주</td>
      <td>이부진</td>
      <td>계열회사 임원</td>
      <td>0</td>
      <td>0.00</td>
      <td>137,755</td>
      <td>0.02</td>
      <td>상속</td>
    </tr>
    <tr>
      <th>8</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>이서현</td>
      <td>최대주주의 특수관계인</td>
      <td>0</td>
      <td>0.00</td>
      <td>55,394,044</td>
      <td>0.93</td>
      <td>상속</td>
    </tr>
    <tr>
      <th>9</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>우선주</td>
      <td>이서현</td>
      <td>최대주주의 특수관계인</td>
      <td>0</td>
      <td>0.00</td>
      <td>137,755</td>
      <td>0.02</td>
      <td>상속</td>
    </tr>
    <tr>
      <th>10</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>김기남</td>
      <td>계열회사 임원</td>
      <td>200,000</td>
      <td>0.00</td>
      <td>210,000</td>
      <td>0.00</td>
      <td>장내매매</td>
    </tr>
    <tr>
      <th>11</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>우선주</td>
      <td>이건희</td>
      <td>-</td>
      <td>619,900</td>
      <td>0.08</td>
      <td>0</td>
      <td>0.00</td>
      <td>피상속</td>
    </tr>
    <tr>
      <th>12</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>김현석</td>
      <td>계열회사 임원</td>
      <td>99,750</td>
      <td>0.00</td>
      <td>99,750</td>
      <td>0.00</td>
      <td>-</td>
    </tr>
    <tr>
      <th>13</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>고동진</td>
      <td>계열회사 임원</td>
      <td>75,000</td>
      <td>0.00</td>
      <td>75,000</td>
      <td>0.00</td>
      <td>-</td>
    </tr>
    <tr>
      <th>14</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>한종희</td>
      <td>계열회사 임원</td>
      <td>5,000</td>
      <td>0.00</td>
      <td>5,000</td>
      <td>0.00</td>
      <td>-</td>
    </tr>
    <tr>
      <th>15</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>박병국</td>
      <td>계열회사 임원</td>
      <td>0</td>
      <td>0.00</td>
      <td>1,000</td>
      <td>0.00</td>
      <td>장내매매</td>
    </tr>
    <tr>
      <th>16</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>안규리</td>
      <td>계열회사 임원</td>
      <td>2,600</td>
      <td>0.00</td>
      <td>3,800</td>
      <td>0.00</td>
      <td>장내매매</td>
    </tr>
    <tr>
      <th>17</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>김한조</td>
      <td>계열회사 임원</td>
      <td>2,175</td>
      <td>0.00</td>
      <td>2,175</td>
      <td>0.00</td>
      <td>-</td>
    </tr>
    <tr>
      <th>18</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>삼성생명보험㈜</td>
      <td>최대주주 본인</td>
      <td>508,157,148</td>
      <td>8.51</td>
      <td>508,157,148</td>
      <td>8.51</td>
      <td>-</td>
    </tr>
    <tr>
      <th>19</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>우선주</td>
      <td>삼성생명보험㈜</td>
      <td>최대주주 본인</td>
      <td>43,950</td>
      <td>0.01</td>
      <td>43,950</td>
      <td>0.01</td>
      <td>-</td>
    </tr>
    <tr>
      <th>20</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>삼성생명보험㈜(특별계정)</td>
      <td>최대주주 본인</td>
      <td>16,284,877</td>
      <td>0.27</td>
      <td>13,860,804</td>
      <td>0.23</td>
      <td>장내매매</td>
    </tr>
    <tr>
      <th>21</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>우선주</td>
      <td>삼성생명보험㈜(특별계정)</td>
      <td>최대주주 본인</td>
      <td>772,567</td>
      <td>0.09</td>
      <td>548,463</td>
      <td>0.07</td>
      <td>장내매매</td>
    </tr>
    <tr>
      <th>22</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>삼성물산㈜</td>
      <td>계열회사</td>
      <td>298,818,100</td>
      <td>5.01</td>
      <td>298,818,100</td>
      <td>5.01</td>
      <td>-</td>
    </tr>
    <tr>
      <th>23</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>삼성화재해상보험㈜</td>
      <td>계열회사</td>
      <td>88,802,052</td>
      <td>1.49</td>
      <td>88,802,052</td>
      <td>1.49</td>
      <td>-</td>
    </tr>
    <tr>
      <th>24</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>삼성복지재단</td>
      <td>출연 재단</td>
      <td>4,484,150</td>
      <td>0.08</td>
      <td>4,484,150</td>
      <td>0.08</td>
      <td>-</td>
    </tr>
    <tr>
      <th>25</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>보통주</td>
      <td>계</td>
      <td>NaN</td>
      <td>1,264,258,552</td>
      <td>21.18</td>
      <td>1,261,846,679</td>
      <td>21.14</td>
      <td>-</td>
    </tr>
    <tr>
      <th>26</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>우선주</td>
      <td>계</td>
      <td>NaN</td>
      <td>1,436,417</td>
      <td>0.17</td>
      <td>1,212,313</td>
      <td>0.15</td>
      <td>-</td>
    </tr>
  </tbody>
</table>
</div>




```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.info.hyslr_sttus(corp_code, '2021', '11011')

pd.DataFrame(data['list'])[['nm','bsis_posesn_stock_qota_rt','trmend_posesn_stock_qota_rt']]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>nm</th>
      <th>bsis_posesn_stock_qota_rt</th>
      <th>trmend_posesn_stock_qota_rt</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>이건희</td>
      <td>4.18</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>1</th>
      <td>삼성문화재단</td>
      <td>0.03</td>
      <td>0.03</td>
    </tr>
    <tr>
      <th>2</th>
      <td>홍라희</td>
      <td>0.91</td>
      <td>2.30</td>
    </tr>
    <tr>
      <th>3</th>
      <td>홍라희</td>
      <td>0.00</td>
      <td>0.03</td>
    </tr>
    <tr>
      <th>4</th>
      <td>이재용</td>
      <td>0.70</td>
      <td>1.63</td>
    </tr>
    <tr>
      <th>5</th>
      <td>이재용</td>
      <td>0.00</td>
      <td>0.02</td>
    </tr>
    <tr>
      <th>6</th>
      <td>이부진</td>
      <td>0.00</td>
      <td>0.93</td>
    </tr>
    <tr>
      <th>7</th>
      <td>이부진</td>
      <td>0.00</td>
      <td>0.02</td>
    </tr>
    <tr>
      <th>8</th>
      <td>이서현</td>
      <td>0.00</td>
      <td>0.93</td>
    </tr>
    <tr>
      <th>9</th>
      <td>이서현</td>
      <td>0.00</td>
      <td>0.02</td>
    </tr>
    <tr>
      <th>10</th>
      <td>김기남</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>11</th>
      <td>이건희</td>
      <td>0.08</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>12</th>
      <td>김현석</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>13</th>
      <td>고동진</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>14</th>
      <td>한종희</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>15</th>
      <td>박병국</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>16</th>
      <td>안규리</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>17</th>
      <td>김한조</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>18</th>
      <td>삼성생명보험㈜</td>
      <td>8.51</td>
      <td>8.51</td>
    </tr>
    <tr>
      <th>19</th>
      <td>삼성생명보험㈜</td>
      <td>0.01</td>
      <td>0.01</td>
    </tr>
    <tr>
      <th>20</th>
      <td>삼성생명보험㈜(특별계정)</td>
      <td>0.27</td>
      <td>0.23</td>
    </tr>
    <tr>
      <th>21</th>
      <td>삼성생명보험㈜(특별계정)</td>
      <td>0.09</td>
      <td>0.07</td>
    </tr>
    <tr>
      <th>22</th>
      <td>삼성물산㈜</td>
      <td>5.01</td>
      <td>5.01</td>
    </tr>
    <tr>
      <th>23</th>
      <td>삼성화재해상보험㈜</td>
      <td>1.49</td>
      <td>1.49</td>
    </tr>
    <tr>
      <th>24</th>
      <td>삼성복지재단</td>
      <td>0.08</td>
      <td>0.08</td>
    </tr>
    <tr>
      <th>25</th>
      <td>계</td>
      <td>21.18</td>
      <td>21.14</td>
    </tr>
    <tr>
      <th>26</th>
      <td>계</td>
      <td>0.17</td>
      <td>0.15</td>
    </tr>
  </tbody>
</table>
</div>



임원 현


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.info.exctv_sttus(corp_code, '2021', '11011')

pd.DataFrame(data['list'])
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>corp_cls</th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>nm</th>
      <th>sexdstn</th>
      <th>birth_ym</th>
      <th>ofcps</th>
      <th>rgist_exctv_at</th>
      <th>fte_at</th>
      <th>chrg_job</th>
      <th>main_career</th>
      <th>mxmm_shrholdr_relate</th>
      <th>hffc_pd</th>
      <th>tenure_end_on</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>김기남</td>
      <td>남</td>
      <td>1958년 04월</td>
      <td>회장</td>
      <td>사내이사</td>
      <td>상근</td>
      <td>ㆍ대표이사ㆍ종합기술원 회장</td>
      <td>ㆍUCLA 전자공학 박사ㆍ삼성전자 DS부문장</td>
      <td>계열회사\n임원</td>
      <td>46개월</td>
      <td>2024년 03월 22일</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>안규리</td>
      <td>여</td>
      <td>1955년 03월</td>
      <td>이사</td>
      <td>사외이사</td>
      <td>비상근</td>
      <td>ㆍ사외이사후보추천위원회위원ㆍ지속가능경영위원회 위원</td>
      <td>ㆍ서울대 내과학 박사\nㆍ서울대 의과대학 신장내과 \n   명예교수</td>
      <td>계열회사\n임원</td>
      <td>34개월</td>
      <td>2022년 03월 19일</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>김한조</td>
      <td>남</td>
      <td>1956년 07월</td>
      <td>이사</td>
      <td>사외이사</td>
      <td>비상근</td>
      <td>ㆍ감사위원회위원\nㆍ내부거래위원회위원\nㆍ지속가능경영위원회 위원</td>
      <td>ㆍ연세대 불어불문학 학사\nㆍ하나금융공익재단 이사장</td>
      <td>계열회사\n임원</td>
      <td>34개월</td>
      <td>2022년 03월 19일</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>김현석</td>
      <td>남</td>
      <td>1961년 01월</td>
      <td>고문</td>
      <td>사내이사</td>
      <td>상근</td>
      <td>ㆍ대표이사ㆍ미래기술담당</td>
      <td>ㆍPortland주립대\n   전기및전자공학석사ㆍ삼성전자 CE부문장</td>
      <td>계열회사\n임원</td>
      <td>46개월</td>
      <td>2024년 03월 22일</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>고동진</td>
      <td>남</td>
      <td>1961년 03월</td>
      <td>고문</td>
      <td>사내이사</td>
      <td>상근</td>
      <td>ㆍ대표이사ㆍ인재혁신담당</td>
      <td>ㆍSussex대 기술정책학 석사ㆍ삼성전자 IM부문장</td>
      <td>계열회사\n임원</td>
      <td>46개월</td>
      <td>2024년 03월 22일</td>
    </tr>
    <tr>
      <th>5</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>한종희</td>
      <td>남</td>
      <td>1962년 03월</td>
      <td>부회장</td>
      <td>사내이사</td>
      <td>상근</td>
      <td>ㆍDX부문장ㆍ영상디스플레이사업부장</td>
      <td>ㆍ인하대 전자공학 학사\nㆍ삼성전자 영상디스플레이사업부장</td>
      <td>계열회사\n임원</td>
      <td>22개월</td>
      <td>2023년 03월 17일</td>
    </tr>
    <tr>
      <th>6</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>최윤호</td>
      <td>남</td>
      <td>1963년 01월</td>
      <td>사장</td>
      <td>사내이사</td>
      <td>상근</td>
      <td>ㆍCFO</td>
      <td>ㆍ성균관대 경영학 학사ㆍ삼성전자 경영지원실장</td>
      <td>계열회사 임원</td>
      <td>22개월</td>
      <td>2023년 03월 17일</td>
    </tr>
    <tr>
      <th>7</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>박재완</td>
      <td>남</td>
      <td>1955년 01월</td>
      <td>이사</td>
      <td>사외이사</td>
      <td>비상근</td>
      <td>ㆍ이사회 의장ㆍ감사위원회 위원장\nㆍ내부거래위원회 위원\nㆍ보상위원회 위원\nㆍ지속...</td>
      <td>ㆍHarvard대 정책학 박사ㆍ성균관대 국정전문대학원 \n   명예교수</td>
      <td>계열회사\n임원</td>
      <td>70개월</td>
      <td>2022년 03월 19일</td>
    </tr>
    <tr>
      <th>8</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>김선욱</td>
      <td>여</td>
      <td>1952년 12월</td>
      <td>이사</td>
      <td>사외이사</td>
      <td>비상근</td>
      <td>ㆍ감사위원회 위원\nㆍ내부거래위원회 위원장ㆍ지속가능경영위원회 위원</td>
      <td>ㆍKonstanz대 법학 박사ㆍ이화여대 명예교수</td>
      <td>계열회사\n임원</td>
      <td>46개월</td>
      <td>2024년 03월 22일</td>
    </tr>
    <tr>
      <th>9</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>박병국</td>
      <td>남</td>
      <td>1959년 04월</td>
      <td>이사</td>
      <td>사외이사</td>
      <td>비상근</td>
      <td>ㆍ사외이사후보추천위원회위원ㆍ보상위원회위원장\nㆍ지속가능경영위원회 위원</td>
      <td>ㆍStanford대 전기공학 박사ㆍ서울대 전기ㆍ정보공학부 교수</td>
      <td>계열회사\n임원</td>
      <td>46개월</td>
      <td>2024년 03월 22일</td>
    </tr>
    <tr>
      <th>10</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>김종훈</td>
      <td>남</td>
      <td>1960년 08월</td>
      <td>이사</td>
      <td>사외이사</td>
      <td>비상근</td>
      <td>ㆍ사외이사후보추천위원회위원ㆍ보상위원회위원\nㆍ지속가능경영위원회 위원</td>
      <td>ㆍMaryland대 신뢰성공학 박사ㆍKiswe Mobile 회장</td>
      <td>계열회사\n임원</td>
      <td>46개월</td>
      <td>2024년 03월 22일</td>
    </tr>
  </tbody>
</table>
</div>



직원 현황


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.info.emp_sttus(corp_code, '2021', '11011')

pd.DataFrame(data['list'])
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>corp_cls</th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>sexdstn</th>
      <th>fo_bbm</th>
      <th>reform_bfe_emp_co_rgllbr</th>
      <th>reform_bfe_emp_co_cnttk</th>
      <th>reform_bfe_emp_co_etc</th>
      <th>rgllbr_co</th>
      <th>rgllbr_abacpt_labrr_co</th>
      <th>cnttk_co</th>
      <th>cnttk_abacpt_labrr_co</th>
      <th>sm</th>
      <th>avrg_cnwk_sdytrn</th>
      <th>fyer_salary_totamt</th>
      <th>jan_salary_am</th>
      <th>rm</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>남</td>
      <td>CE</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>10,075</td>
      <td>-</td>
      <td>58</td>
      <td>-</td>
      <td>10,133</td>
      <td>16.1</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>여</td>
      <td>성별합계</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>29,120</td>
      <td>407</td>
      <td>108</td>
      <td>-</td>
      <td>29,228</td>
      <td>11.3</td>
      <td>3,161,517,000,000</td>
      <td>115,000,000</td>
      <td>-</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>여</td>
      <td>CE</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>2,077</td>
      <td>72</td>
      <td>9</td>
      <td>-</td>
      <td>2,086</td>
      <td>11.9</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>남</td>
      <td>IM</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>19,319</td>
      <td>-</td>
      <td>147</td>
      <td>-</td>
      <td>19,466</td>
      <td>14.4</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>여</td>
      <td>IM</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>6,941</td>
      <td>72</td>
      <td>19</td>
      <td>-</td>
      <td>6,960</td>
      <td>12.8</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <th>5</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>남</td>
      <td>DS</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>45,923</td>
      <td>-</td>
      <td>144</td>
      <td>-</td>
      <td>46,067</td>
      <td>10.0</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <th>6</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>여</td>
      <td>DS</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>17,813</td>
      <td>182</td>
      <td>22</td>
      <td>-</td>
      <td>17,835</td>
      <td>10.8</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <th>7</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>남</td>
      <td>기타</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>8,431</td>
      <td>-</td>
      <td>160</td>
      <td>-</td>
      <td>8,591</td>
      <td>15.0</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <th>8</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>여</td>
      <td>기타</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>2,289</td>
      <td>81</td>
      <td>58</td>
      <td>-</td>
      <td>2,347</td>
      <td>11.8</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <th>9</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>남</td>
      <td>성별합계</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>83,748</td>
      <td>-</td>
      <td>509</td>
      <td>-</td>
      <td>84,257</td>
      <td>12.2</td>
      <td>12,683,498,000,000</td>
      <td>154,000,000</td>
      <td>-</td>
    </tr>
  </tbody>
</table>
</div>



이사 보수


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.info.hmv_audit_indvdl_by_sttus(corp_code, '2021', '11011')

pd.DataFrame(data['list'])
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>corp_cls</th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>nm</th>
      <th>ofcps</th>
      <th>mendng_totamt</th>
      <th>mendng_totamt_ct_incls_mendng</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>최윤호</td>
      <td>이사</td>
      <td>3,414,000,000</td>
      <td>-</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>한종희</td>
      <td>이사</td>
      <td>4,505,000,000</td>
      <td>-</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>김기남</td>
      <td>대표이사</td>
      <td>8,644,000,000</td>
      <td>-</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>김현석</td>
      <td>대표이사</td>
      <td>10,334,000,000</td>
      <td>-</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>고동진</td>
      <td>대표이사</td>
      <td>11,838,000,000</td>
      <td>-</td>
    </tr>
  </tbody>
</table>
</div>



연봉 top 5


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.info.indvdl_by_pay(corp_code, '2021', '11011')

pd.DataFrame(data['list'])
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>corp_cls</th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>nm</th>
      <th>ofcps</th>
      <th>mendng_totamt</th>
      <th>mendng_totamt_ct_incls_mendng</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>고동진</td>
      <td>고문</td>
      <td>11,838,000,000</td>
      <td>-</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>김현석</td>
      <td>고문</td>
      <td>10,334,000,000</td>
      <td>-</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>김상균</td>
      <td>고문</td>
      <td>9,569,000,000</td>
      <td>-</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>이상훈</td>
      <td>고문</td>
      <td>8,745,000,000</td>
      <td>-</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>김기남</td>
      <td>회장</td>
      <td>8,644,000,000</td>
      <td>-</td>
    </tr>
  </tbody>
</table>
</div>



타법인 출자 현


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.info.otr_cpr_invstmnt_sttus(corp_code, '2021', '11011')

pd.DataFrame(data['list'])
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>corp_cls</th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>inv_prm</th>
      <th>frst_acqs_de</th>
      <th>invstmnt_purps</th>
      <th>frst_acqs_amount</th>
      <th>bsis_blce_qy</th>
      <th>bsis_blce_qota_rt</th>
      <th>bsis_blce_acntbk_amount</th>
      <th>incrs_dcrs_acqs_dsps_qy</th>
      <th>incrs_dcrs_acqs_dsps_amount</th>
      <th>incrs_dcrs_evl_lstmn</th>
      <th>trmend_blce_qy</th>
      <th>trmend_blce_qota_rt</th>
      <th>trmend_blce_acntbk_amount</th>
      <th>recent_bsns_year_fnnr_sttus_tot_assets</th>
      <th>recent_bsns_year_fnnr_sttus_thstrm_ntpf</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>삼성전기㈜</td>
      <td>1977.01.01</td>
      <td>경영참여</td>
      <td>250,000,000</td>
      <td>17,693,000</td>
      <td>23.7</td>
      <td>445,244,000,000</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>17,693,000</td>
      <td>23.7</td>
      <td>445,244,000,000</td>
      <td>9,957,485,000,000</td>
      <td>917,737,000,000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>세메스㈜</td>
      <td>1992.12.31</td>
      <td>경영참여</td>
      <td>1,000,000,000</td>
      <td>2,173,000</td>
      <td>91.5</td>
      <td>71,906,000,000</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>2,173,000</td>
      <td>91.5</td>
      <td>71,906,000,000</td>
      <td>1,931,476,000,000</td>
      <td>264,309,000,000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>SAPL</td>
      <td>2006.07.01</td>
      <td>경영참여</td>
      <td>793,000,000</td>
      <td>877,133,000</td>
      <td>100.0</td>
      <td>981,483,000,000</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>877,133,000</td>
      <td>100.0</td>
      <td>981,483,000,000</td>
      <td>669,485,000,000</td>
      <td>20,355,000,000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>SME</td>
      <td>2003.05.01</td>
      <td>경영참여</td>
      <td>4,796,000,000</td>
      <td>17,100,000</td>
      <td>100.0</td>
      <td>7,644,000,000</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>17,100,000</td>
      <td>100.0</td>
      <td>7,644,000,000</td>
      <td>625,662,000,000</td>
      <td>19,314,000,000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>SDMA</td>
      <td>1995.03.01</td>
      <td>경영참여</td>
      <td>21,876,000,000</td>
      <td>71,400,000</td>
      <td>75.0</td>
      <td>18,741,000,000</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>71,400,000</td>
      <td>75.0</td>
      <td>18,741,000,000</td>
      <td>24,681,000,000</td>
      <td>-716,000,000</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>141</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>SEO</td>
      <td>1997.01.01</td>
      <td>경영참여</td>
      <td>120,000,000</td>
      <td>-</td>
      <td>100.0</td>
      <td>-10,043,000,000</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>100.0</td>
      <td>-10,043,000,000</td>
      <td>1,863,000,000</td>
      <td>-166,000,000</td>
    </tr>
    <tr>
      <th>142</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>SGE</td>
      <td>1995.05.25</td>
      <td>경영참여</td>
      <td>827,000,000</td>
      <td>-</td>
      <td>100.0</td>
      <td>32,836,000,000</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>100.0</td>
      <td>32,836,000,000</td>
      <td>1,776,336,000,000</td>
      <td>30,755,000,000</td>
    </tr>
    <tr>
      <th>143</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>SEEG</td>
      <td>2012.07.09</td>
      <td>경영참여</td>
      <td>23,000,000</td>
      <td>-</td>
      <td>0.1</td>
      <td>39,000,000</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>0.1</td>
      <td>39,000,000</td>
      <td>946,599,000,000</td>
      <td>56,203,000,000</td>
    </tr>
    <tr>
      <th>144</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>SSA</td>
      <td>1998.12.01</td>
      <td>경영참여</td>
      <td>263,000,000</td>
      <td>2,000,000</td>
      <td>100.0</td>
      <td>32,622,000,000</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>2,000,000</td>
      <td>100.0</td>
      <td>32,622,000,000</td>
      <td>500,605,000,000</td>
      <td>37,741,000,000</td>
    </tr>
    <tr>
      <th>145</th>
      <td>20220308000798</td>
      <td>Y</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>합계</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>58,130,298,000,000</td>
      <td>25,035,105,000</td>
      <td>-169,101,000,000</td>
      <td>-70,931,000,000</td>
      <td>-</td>
      <td>-</td>
      <td>57,890,266,000,000</td>
      <td>-</td>
      <td>-</td>
    </tr>
  </tbody>
</table>
<p>146 rows × 19 columns</p>
</div>



상장기업 재무정보


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.finance.fnltt_singl_acnt(corp_code, '2021', '11011')

pd.DataFrame(data['list'])
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>reprt_code</th>
      <th>bsns_year</th>
      <th>corp_code</th>
      <th>stock_code</th>
      <th>fs_div</th>
      <th>fs_nm</th>
      <th>sj_div</th>
      <th>sj_nm</th>
      <th>account_nm</th>
      <th>...</th>
      <th>thstrm_dt</th>
      <th>thstrm_amount</th>
      <th>frmtrm_nm</th>
      <th>frmtrm_dt</th>
      <th>frmtrm_amount</th>
      <th>bfefrmtrm_nm</th>
      <th>bfefrmtrm_dt</th>
      <th>bfefrmtrm_amount</th>
      <th>ord</th>
      <th>currency</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>유동자산</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>218,163,185,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>198,215,579,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>181,385,260,000,000</td>
      <td>1</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>비유동자산</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>208,457,973,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>180,020,139,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>171,179,237,000,000</td>
      <td>3</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>자산총계</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>426,621,158,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>378,235,718,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>352,564,497,000,000</td>
      <td>5</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>유동부채</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>88,117,133,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>75,604,351,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>63,782,764,000,000</td>
      <td>7</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>비유동부채</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>33,604,094,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>26,683,351,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>25,901,312,000,000</td>
      <td>9</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>5</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>부채총계</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>121,721,227,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>102,287,702,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>89,684,076,000,000</td>
      <td>11</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>6</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>자본금</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>897,514,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>897,514,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>897,514,000,000</td>
      <td>13</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>7</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>이익잉여금</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>293,064,763,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>271,068,211,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>254,582,894,000,000</td>
      <td>17</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>8</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>자본총계</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>304,899,931,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>275,948,016,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>262,880,421,000,000</td>
      <td>21</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>9</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>매출액</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>279,604,799,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>236,806,988,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>230,400,881,000,000</td>
      <td>23</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>10</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>영업이익</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>51,633,856,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>35,993,876,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>27,768,509,000,000</td>
      <td>25</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>11</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>법인세차감전 순이익</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>53,351,827,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>36,345,117,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>30,432,189,000,000</td>
      <td>27</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>12</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>당기순이익</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>39,907,450,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>26,407,832,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>21,738,865,000,000</td>
      <td>29</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>13</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>당기순이익(손실)</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>39,907,450,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>26,407,832,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>21,738,865,000,000</td>
      <td>61</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>14</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>유동자산</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>73,553,416,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>73,798,549,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>72,659,080,000,000</td>
      <td>2</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>15</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>비유동자산</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>177,558,768,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>155,865,878,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>143,521,840,000,000</td>
      <td>4</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>16</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>자산총계</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>251,112,184,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>229,664,427,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>216,180,920,000,000</td>
      <td>6</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>17</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>유동부채</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>53,067,303,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>44,412,904,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>36,237,164,000,000</td>
      <td>8</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>18</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>비유동부채</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>4,851,149,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>1,934,799,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>2,073,509,000,000</td>
      <td>10</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>19</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>부채총계</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>57,918,452,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>46,347,703,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>38,310,673,000,000</td>
      <td>12</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>20</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>자본금</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>897,514,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>897,514,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>897,514,000,000</td>
      <td>15</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>21</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>이익잉여금</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>188,774,335,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>178,284,102,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>172,288,326,000,000</td>
      <td>19</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>22</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>자본총계</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>193,193,732,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>183,316,724,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>177,870,247,000,000</td>
      <td>22</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>23</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>매출액</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>199,744,705,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>166,311,191,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>154,772,859,000,000</td>
      <td>24</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>24</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>영업이익</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>31,993,162,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>20,518,974,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>14,115,067,000,000</td>
      <td>26</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>25</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>법인세차감전 순이익</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>38,704,492,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>20,451,923,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>19,032,469,000,000</td>
      <td>28</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>26</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>당기순이익</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>30,970,954,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>15,615,018,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>15,353,323,000,000</td>
      <td>30</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>27</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>당기순이익(손실)</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>30,970,954,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>15,615,018,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>15,353,323,000,000</td>
      <td>62</td>
      <td>KRW</td>
    </tr>
  </tbody>
</table>
<p>28 rows × 21 columns</p>
</div>



모든 항목을 보고싶다면 아래와 같이 한다. (CFS:연결재무제표 인지, OFS:재무제표 인지를 선택하여 추가로 넣는다.)


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.finance.fnltt_singl_acnt_all(corp_code, '2021', '11011', 'CFS')

pd.DataFrame(data['list'])
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>reprt_code</th>
      <th>bsns_year</th>
      <th>corp_code</th>
      <th>sj_div</th>
      <th>sj_nm</th>
      <th>account_id</th>
      <th>account_nm</th>
      <th>account_detail</th>
      <th>thstrm_nm</th>
      <th>thstrm_amount</th>
      <th>frmtrm_nm</th>
      <th>frmtrm_amount</th>
      <th>bfefrmtrm_nm</th>
      <th>bfefrmtrm_amount</th>
      <th>ord</th>
      <th>currency</th>
      <th>thstrm_add_amount</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>ifrs-full_CurrentAssets</td>
      <td>유동자산</td>
      <td>-</td>
      <td>제 53 기</td>
      <td>218163185000000</td>
      <td>제 52 기</td>
      <td>198215579000000</td>
      <td>제 51 기</td>
      <td>181385260000000</td>
      <td>1</td>
      <td>KRW</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>ifrs-full_CashAndCashEquivalents</td>
      <td>현금및현금성자산</td>
      <td>-</td>
      <td>제 53 기</td>
      <td>39031415000000</td>
      <td>제 52 기</td>
      <td>29382578000000</td>
      <td>제 51 기</td>
      <td>26885999000000</td>
      <td>2</td>
      <td>KRW</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>dart_ShortTermDepositsNotClassifiedAsCashEquiv...</td>
      <td>단기금융상품</td>
      <td>-</td>
      <td>제 53 기</td>
      <td>81708986000000</td>
      <td>제 52 기</td>
      <td>92441703000000</td>
      <td>제 51 기</td>
      <td>76252052000000</td>
      <td>3</td>
      <td>KRW</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>-표준계정코드 미사용-</td>
      <td>단기상각후원가금융자산</td>
      <td>-</td>
      <td>제 53 기</td>
      <td>3369034000000</td>
      <td>제 52 기</td>
      <td>2757111000000</td>
      <td>제 51 기</td>
      <td>3914216000000</td>
      <td>4</td>
      <td>KRW</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>ifrs-full_CurrentFinancialAssetsAtFairValueThr...</td>
      <td>단기당기손익-공정가치금융자산</td>
      <td>-</td>
      <td>제 53 기</td>
      <td>40757000000</td>
      <td>제 52 기</td>
      <td>71451000000</td>
      <td>제 51 기</td>
      <td>1727436000000</td>
      <td>5</td>
      <td>KRW</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>181</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>SCE</td>
      <td>자본변동표</td>
      <td>ifrs-full_Equity</td>
      <td>기말자본</td>
      <td>자본 [member]|지배기업 소유주지분|기타자본항목</td>
      <td>제 53 기</td>
      <td>-2128473000000</td>
      <td>제 52 기</td>
      <td>-8687155000000</td>
      <td>제 51 기</td>
      <td>-4968829000000</td>
      <td>13</td>
      <td>KRW</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>182</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>SCE</td>
      <td>자본변동표</td>
      <td>ifrs-full_Equity</td>
      <td>기말자본</td>
      <td>자본 [member]|지배기업 소유주지분</td>
      <td>제 53 기</td>
      <td>296237697000000</td>
      <td>제 52 기</td>
      <td>267670331000000</td>
      <td>제 51 기</td>
      <td>254915472000000</td>
      <td>13</td>
      <td>KRW</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>183</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>SCE</td>
      <td>자본변동표</td>
      <td>ifrs-full_Equity</td>
      <td>기말자본</td>
      <td>자본 [member]|비지배지분 [member]</td>
      <td>제 53 기</td>
      <td>8662234000000</td>
      <td>제 52 기</td>
      <td>8277685000000</td>
      <td>제 51 기</td>
      <td>7964949000000</td>
      <td>13</td>
      <td>KRW</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>184</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>SCE</td>
      <td>자본변동표</td>
      <td>ifrs-full_Equity</td>
      <td>기말자본</td>
      <td>연결재무제표 [member]</td>
      <td>제 53 기</td>
      <td>304899931000000</td>
      <td>제 52 기</td>
      <td>275948016000000</td>
      <td>제 51 기</td>
      <td>262880421000000</td>
      <td>13</td>
      <td>KRW</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>185</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>SCE</td>
      <td>자본변동표</td>
      <td>ifrs-full_Equity</td>
      <td>기말자본</td>
      <td>자본 [member]|지배기업 소유주지분|이익잉여금 [member]</td>
      <td>제 53 기</td>
      <td>293064763000000</td>
      <td>제 52 기</td>
      <td>271068211000000</td>
      <td>제 51 기</td>
      <td>254582894000000</td>
      <td>13</td>
      <td>KRW</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>186 rows × 18 columns</p>
</div>



임원, 주요 주주 소유 보고 : Open DART API에서 '지분공시 종합정보


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.shareholder.elestock(corp_code)

pd.DataFrame(data['list'])
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>rcept_dt</th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>repror</th>
      <th>isu_exctv_rgist_at</th>
      <th>isu_exctv_ofcps</th>
      <th>isu_main_shrholdr</th>
      <th>sp_stock_lmp_cnt</th>
      <th>sp_stock_lmp_irds_cnt</th>
      <th>sp_stock_lmp_rate</th>
      <th>sp_stock_lmp_irds_rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20211129000088</td>
      <td>2021-11-29</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>안규리</td>
      <td>등기임원</td>
      <td>사외이사</td>
      <td>-</td>
      <td>3,700</td>
      <td>100</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20211213000154</td>
      <td>2021-12-13</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>심황윤</td>
      <td>비등기임원</td>
      <td>상무</td>
      <td>-</td>
      <td>1,000</td>
      <td>1,000</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20211214000171</td>
      <td>2021-12-14</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>손성민</td>
      <td>비등기임원</td>
      <td>상무</td>
      <td>-</td>
      <td>130</td>
      <td>130</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20211214000105</td>
      <td>2021-12-14</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>한상섭</td>
      <td>비등기임원</td>
      <td>상무</td>
      <td>-</td>
      <td>928</td>
      <td>928</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20211214000004</td>
      <td>2021-12-14</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>김유나</td>
      <td>비등기임원</td>
      <td>상무</td>
      <td>-</td>
      <td>176</td>
      <td>176</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>194</th>
      <td>20230925000568</td>
      <td>2023-09-26</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>손현석</td>
      <td>비등기임원</td>
      <td>상무</td>
      <td>-</td>
      <td>246</td>
      <td>246</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>195</th>
      <td>20231010000607</td>
      <td>2023-10-10</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>이훈신</td>
      <td>비등기임원</td>
      <td>상무</td>
      <td>-</td>
      <td>140</td>
      <td>140</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>196</th>
      <td>20231012000235</td>
      <td>2023-10-12</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>최경식</td>
      <td>비등기임원</td>
      <td>사장</td>
      <td>-</td>
      <td>5,000</td>
      <td>5,000</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>197</th>
      <td>20231026000314</td>
      <td>2023-10-26</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>허길영</td>
      <td>비등기임원</td>
      <td>부사장</td>
      <td>-</td>
      <td>1,683</td>
      <td>-2,250</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>198</th>
      <td>20231109000233</td>
      <td>2023-11-09</td>
      <td>00126380</td>
      <td>삼성전자</td>
      <td>황기현</td>
      <td>비등기임원</td>
      <td>부사장</td>
      <td>-</td>
      <td>751</td>
      <td>751</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
  </tbody>
</table>
<p>199 rows × 12 columns</p>
</div>



 - 특정 사람(CEO)에 대해서만 보기


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.shareholder.elestock(corp_code)

df_temp = pd.DataFrame(data['list'])
df_temp[df_temp['repror'] == '이재용']
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>rcept_dt</th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>repror</th>
      <th>isu_exctv_rgist_at</th>
      <th>isu_exctv_ofcps</th>
      <th>isu_main_shrholdr</th>
      <th>sp_stock_lmp_cnt</th>
      <th>sp_stock_lmp_irds_cnt</th>
      <th>sp_stock_lmp_rate</th>
      <th>sp_stock_lmp_irds_rate</th>
    </tr>
  </thead>
  <tbody>
  </tbody>
</table>
</div>



재미로 하는 시총 Top 50 社 - 연봉왕 뽑아보기

 * 한 종목에 대해 뽑아보기   
  - 기업 데이터를 끌어와, 표로 만들어본다.


```python
corp_code = df_listed[df_listed['corp_name'] == '카카오'].iloc[0,0]
data = dart_fss.api.info.indvdl_by_pay(corp_code, '2021', '11011')

pd.DataFrame(data['list'])
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>corp_cls</th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>nm</th>
      <th>ofcps</th>
      <th>mendng_totamt</th>
      <th>mendng_totamt_ct_incls_mendng</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>신정환</td>
      <td>신사업 담당</td>
      <td>12,874,000,000</td>
      <td>-</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>배재현</td>
      <td>CAC 투자거버넌스 총괄</td>
      <td>8,261,000,000</td>
      <td>-</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>권승조</td>
      <td>(前) 지적재산부문 책임자</td>
      <td>6,535,000,000</td>
      <td>-</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>남궁훈</td>
      <td>카카오 OTF 장</td>
      <td>6,158,000,000</td>
      <td>-</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>안성진</td>
      <td>(前) M사업전략 자문</td>
      <td>5,750,000,000</td>
      <td>-</td>
    </tr>
  </tbody>
</table>
</div>



- 아래와 같이 컬럼명을 바꿔서 뽑아볼 수 있다.


```python
corp_code = df_listed[df_listed['corp_name'] == '카카오'].iloc[0,0]
data = dart_fss.api.info.indvdl_by_pay(corp_code, '2021', '11011')

df = pd.DataFrame(data['list'])
df = df[['corp_name','nm','ofcps','mendng_totamt']]
df.columns = ['기업명','이름','역할','보수']
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>기업명</th>
      <th>이름</th>
      <th>역할</th>
      <th>보수</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>카카오</td>
      <td>신정환</td>
      <td>신사업 담당</td>
      <td>12,874,000,000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>카카오</td>
      <td>배재현</td>
      <td>CAC 투자거버넌스 총괄</td>
      <td>8,261,000,000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>카카오</td>
      <td>권승조</td>
      <td>(前) 지적재산부문 책임자</td>
      <td>6,535,000,000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>카카오</td>
      <td>남궁훈</td>
      <td>카카오 OTF 장</td>
      <td>6,158,000,000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>카카오</td>
      <td>안성진</td>
      <td>(前) M사업전략 자문</td>
      <td>5,750,000,000</td>
    </tr>
  </tbody>
</table>
</div>



 - 보수 금액을 문자열에서 숫자형으로 바꾸기


```python
corp_code = df_listed[df_listed['corp_name'] == '카카오'].iloc[0,0]
data = dart_fss.api.info.indvdl_by_pay(corp_code, '2021', '11011')

df = pd.DataFrame(data['list'])


df = df[['corp_name','nm','ofcps','mendng_totamt']]

df.columns = ['기업명','이름','역할','보수']
df['보수'] = pd.to_numeric(df['보수'].str.replace(',',''))
df.dtypes
```




    기업명    object
    이름     object
    역할     object
    보수      int64
    dtype: object



- 보수 금액을 오름차순/내림차순으로 정렬해본다.


```python
corp_code = df_listed[df_listed['corp_name'] == '카카오'].iloc[0,0]
data = dart_fss.api.info.indvdl_by_pay(corp_code, '2021', '11011')

df = pd.DataFrame(data['list'])


df = df[['corp_name','nm','ofcps','mendng_totamt']]

df.columns = ['기업명','이름','역할','보수']
df['보수'] = pd.to_numeric(df['보수'].str.replace(',',''))
df.sort_values(by='보수',ascending=False)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>기업명</th>
      <th>이름</th>
      <th>역할</th>
      <th>보수</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>카카오</td>
      <td>신정환</td>
      <td>신사업 담당</td>
      <td>12874000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>카카오</td>
      <td>배재현</td>
      <td>CAC 투자거버넌스 총괄</td>
      <td>8261000000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>카카오</td>
      <td>권승조</td>
      <td>(前) 지적재산부문 책임자</td>
      <td>6535000000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>카카오</td>
      <td>남궁훈</td>
      <td>카카오 OTF 장</td>
      <td>6158000000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>카카오</td>
      <td>안성진</td>
      <td>(前) M사업전략 자문</td>
      <td>5750000000</td>
    </tr>
  </tbody>
</table>
</div>



- 여러 기업에 적용시키기 위해, 함수로 만들어 본다.


```python
def get_salary(name):
  corp_code = df_listed[df_listed['corp_name'] == name].iloc[0,0]
  data = dart_fss.api.info.indvdl_by_pay(corp_code, '2021', '11011')

  df = pd.DataFrame(data['list'])

  df = df[['corp_name','nm','ofcps','mendng_totamt']]

  df.columns = ['기업명','이름','역할','보수']
  df['보수'] = pd.to_numeric(df['보수'].str.replace(',',''))

  return df


```


```python
get_salary('삼성전자')
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>기업명</th>
      <th>이름</th>
      <th>역할</th>
      <th>보수</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>삼성전자</td>
      <td>고동진</td>
      <td>고문</td>
      <td>11838000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>삼성전자</td>
      <td>김현석</td>
      <td>고문</td>
      <td>10334000000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>삼성전자</td>
      <td>김상균</td>
      <td>고문</td>
      <td>9569000000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>삼성전자</td>
      <td>이상훈</td>
      <td>고문</td>
      <td>8745000000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>삼성전자</td>
      <td>김기남</td>
      <td>회장</td>
      <td>8644000000</td>
    </tr>
  </tbody>
</table>
</div>



*여러개 종목에 대해 뽑아보기

  - 50여개 종목을 뽑아, 합쳐준다.


```python
names = ['삼성전자','LG에너지솔루션','SK하이닉스','NAVER','삼성바이오로직스','삼성전자우','카카오','삼성SDI','현대차','LG화학','기아','POSCO홀딩스','KB금융','카카오뱅크','셀트리온','신한지주','삼성물산','현대모비스','SK이노베이션','LG전자','카카오페이','SK','한국전력','크래프톤','하나금융지주','LG생활건강','HMM','삼성생명','하이브','두산중공업','SK텔레콤','삼성전기','SK바이오사이언스','LG','S-Oil','고려아연','KT&G','우리금융지주','대한항공','삼성에스디에스','현대중공업','엔씨소프트','삼성화재','아모레퍼시픽','KT','포스코케미칼','넷마블','SK아이이테크놀로지','LG이노텍','기업은행']

dfs = []
for name in names:
  try:
     df = get_salary(name)
     dfs.append(df)
  except:
     print(f'error- {name}')

df_result = pd.concat(dfs)
df_result
```

    error- 삼성전자우
    error- 현대차
    error- 삼성물산
    error- SK
    error- 한국전력
    error- 두산중공업
    error- KT&G
    error- 우리금융지주
    error- 현대중공업
    error- 삼성화재
    error- KT
    error- 포스코케미칼
    error- SK아이이테크놀로지
    error- 기업은행
    




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>기업명</th>
      <th>이름</th>
      <th>역할</th>
      <th>보수</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>삼성전자</td>
      <td>고동진</td>
      <td>고문</td>
      <td>11838000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>삼성전자</td>
      <td>김현석</td>
      <td>고문</td>
      <td>10334000000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>삼성전자</td>
      <td>김상균</td>
      <td>고문</td>
      <td>9569000000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>삼성전자</td>
      <td>이상훈</td>
      <td>고문</td>
      <td>8745000000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>삼성전자</td>
      <td>김기남</td>
      <td>회장</td>
      <td>8644000000</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>0</th>
      <td>LG이노텍</td>
      <td>정철동</td>
      <td>사장</td>
      <td>2206000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>LG이노텍</td>
      <td>허동영</td>
      <td>전무</td>
      <td>1516000000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>LG이노텍</td>
      <td>이득중</td>
      <td>전무</td>
      <td>1277000000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>LG이노텍</td>
      <td>박창곤</td>
      <td>상무</td>
      <td>886000000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>LG이노텍</td>
      <td>이인규</td>
      <td>부사장</td>
      <td>828000000</td>
    </tr>
  </tbody>
</table>
<p>170 rows × 4 columns</p>
</div>



- 결과 값에서 '보수'의 내림차순으로 정렬해보고, 상위 30개만 뽑아본다.


```python
df_result.sort_values(by='보수',ascending=False).head(30)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>기업명</th>
      <th>이름</th>
      <th>역할</th>
      <th>보수</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>하이브</td>
      <td>강효원</td>
      <td>수석 프로듀서</td>
      <td>40077000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>하이브</td>
      <td>윤석준</td>
      <td>Global CEO</td>
      <td>39229000000</td>
    </tr>
    <tr>
      <th>0</th>
      <td>카카오페이</td>
      <td>류영준</td>
      <td>대표이사</td>
      <td>33776000000</td>
    </tr>
    <tr>
      <th>0</th>
      <td>현대모비스</td>
      <td>정몽구</td>
      <td>대표이사(명예회장)</td>
      <td>30234000000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>하이브</td>
      <td>김신규</td>
      <td>CAMO</td>
      <td>27800000000</td>
    </tr>
    <tr>
      <th>0</th>
      <td>크래프톤</td>
      <td>김효섭</td>
      <td>-</td>
      <td>21805000000</td>
    </tr>
    <tr>
      <th>0</th>
      <td>카카오</td>
      <td>신정환</td>
      <td>신사업 담당</td>
      <td>12874000000</td>
    </tr>
    <tr>
      <th>0</th>
      <td>삼성전자</td>
      <td>고동진</td>
      <td>고문</td>
      <td>11838000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>카카오페이</td>
      <td>이진</td>
      <td>미등기임원</td>
      <td>10820000000</td>
    </tr>
    <tr>
      <th>0</th>
      <td>엔씨소프트</td>
      <td>김택진</td>
      <td>대표이사(CEO)</td>
      <td>10602000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>삼성전자</td>
      <td>김현석</td>
      <td>고문</td>
      <td>10334000000</td>
    </tr>
    <tr>
      <th>0</th>
      <td>카카오뱅크</td>
      <td>윤호영</td>
      <td>대표이사</td>
      <td>9825000000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>삼성전자</td>
      <td>김상균</td>
      <td>고문</td>
      <td>9569000000</td>
    </tr>
    <tr>
      <th>0</th>
      <td>LG</td>
      <td>구광모</td>
      <td>대표이사</td>
      <td>8826000000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>삼성전자</td>
      <td>이상훈</td>
      <td>고문</td>
      <td>8745000000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>삼성전자</td>
      <td>김기남</td>
      <td>회장</td>
      <td>8644000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>카카오</td>
      <td>배재현</td>
      <td>CAC 투자거버넌스 총괄</td>
      <td>8261000000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>카카오페이</td>
      <td>정호윤</td>
      <td>직원</td>
      <td>7480000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>카카오뱅크</td>
      <td>김주원</td>
      <td>기타비상무이사</td>
      <td>7126000000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>카카오</td>
      <td>권승조</td>
      <td>(前) 지적재산부문 책임자</td>
      <td>6535000000</td>
    </tr>
    <tr>
      <th>0</th>
      <td>셀트리온</td>
      <td>서정진</td>
      <td>회장</td>
      <td>6375000000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>카카오</td>
      <td>남궁훈</td>
      <td>카카오 OTF 장</td>
      <td>6158000000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>카카오</td>
      <td>안성진</td>
      <td>(前) M사업전략 자문</td>
      <td>5750000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>크래프톤</td>
      <td>한상근</td>
      <td>직원</td>
      <td>5733000000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>크래프톤</td>
      <td>정수영</td>
      <td>직원</td>
      <td>5722000000</td>
    </tr>
    <tr>
      <th>0</th>
      <td>LG전자</td>
      <td>송대현</td>
      <td>前 사장</td>
      <td>5644000000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>카카오페이</td>
      <td>전재국</td>
      <td>직원</td>
      <td>5504000000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>크래프톤</td>
      <td>권정현</td>
      <td>-</td>
      <td>5447000000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>카카오페이</td>
      <td>나호열</td>
      <td>미등기임원</td>
      <td>5255000000</td>
    </tr>
    <tr>
      <th>0</th>
      <td>NAVER</td>
      <td>최인혁</td>
      <td>사내이사</td>
      <td>4532000000</td>
    </tr>
  </tbody>
</table>
</div>



2) 최대 주주의 주식 변동 모아보기

 * 한 종목에 대해 해보기
  - 우선, 특정 기업의 주요 주주 지분율을 다시 본다.


```python
corp_code = df_listed[df_listed['corp_name'] == '카카오'].iloc[0,0]
data = dart_fss.api.info.hyslr_sttus('00258801', '2021', '11011')

df = pd.DataFrame(data['list'])
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>corp_cls</th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>stock_knd</th>
      <th>nm</th>
      <th>relate</th>
      <th>bsis_posesn_stock_co</th>
      <th>bsis_posesn_stock_qota_rt</th>
      <th>trmend_posesn_stock_co</th>
      <th>trmend_posesn_stock_qota_rt</th>
      <th>rm</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>보통주</td>
      <td>김범수</td>
      <td>본인</td>
      <td>12,500,631</td>
      <td>14.12</td>
      <td>59,124,547</td>
      <td>13.26</td>
      <td>증여 주식분할</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>보통주</td>
      <td>김은정</td>
      <td>특수관계인</td>
      <td>0</td>
      <td>0.00</td>
      <td>71,850</td>
      <td>0.02</td>
      <td>수증, 주식분할</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>보통주</td>
      <td>김진원</td>
      <td>특수관계인</td>
      <td>634</td>
      <td>0.00</td>
      <td>0</td>
      <td>0.00</td>
      <td>수증, 주식분할, 단순매도</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>보통주</td>
      <td>김행자</td>
      <td>특수관계인</td>
      <td>0</td>
      <td>0.00</td>
      <td>100,000</td>
      <td>0.02</td>
      <td>수증, 주식분할</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>보통주</td>
      <td>김현수</td>
      <td>특수관계인</td>
      <td>0</td>
      <td>0.00</td>
      <td>0</td>
      <td>0.00</td>
      <td>단순 매매</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>74</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>보통주</td>
      <td>황인호</td>
      <td>특수관계인</td>
      <td>7,200</td>
      <td>0.01</td>
      <td>0</td>
      <td>0.00</td>
      <td>자사주 상여금 수취, 주식분할, 주식매수선택권 행사,특별관계해소</td>
    </tr>
    <tr>
      <th>75</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>보통주</td>
      <td>김예빈</td>
      <td>특수관계인</td>
      <td>0</td>
      <td>0.00</td>
      <td>268,000</td>
      <td>0.06</td>
      <td>수증, 주식분할</td>
    </tr>
    <tr>
      <th>76</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>보통주</td>
      <td>김유태</td>
      <td>특수관계인</td>
      <td>0</td>
      <td>0.00</td>
      <td>14,700</td>
      <td>0.00</td>
      <td>수증, 주식분할</td>
    </tr>
    <tr>
      <th>77</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>보통주</td>
      <td>계</td>
      <td>NaN</td>
      <td>22,542,030</td>
      <td>25.47</td>
      <td>107,844,461</td>
      <td>24.19</td>
      <td>-</td>
    </tr>
    <tr>
      <th>78</th>
      <td>20220321001331</td>
      <td>Y</td>
      <td>00258801</td>
      <td>카카오</td>
      <td>우선주</td>
      <td>계</td>
      <td>NaN</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
  </tbody>
</table>
<p>79 rows × 12 columns</p>
</div>



- 보고 싶은 컬럼을 뽑고, 컬럼명을 바꿔준다


```python
data = dart_fss.api.info.hyslr_sttus('00258801', '2021', '11011')
df = pd.DataFrame(data['list'])

df = df[['corp_name','nm','relate','bsis_posesn_stock_qota_rt','trmend_posesn_stock_qota_rt','rm']]
df.columns = ['회사명','이름','관계','기초지분율','기말지분율','비고']

df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>회사명</th>
      <th>이름</th>
      <th>관계</th>
      <th>기초지분율</th>
      <th>기말지분율</th>
      <th>비고</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>카카오</td>
      <td>김범수</td>
      <td>본인</td>
      <td>14.12</td>
      <td>13.26</td>
      <td>증여 주식분할</td>
    </tr>
    <tr>
      <th>1</th>
      <td>카카오</td>
      <td>김은정</td>
      <td>특수관계인</td>
      <td>0.00</td>
      <td>0.02</td>
      <td>수증, 주식분할</td>
    </tr>
    <tr>
      <th>2</th>
      <td>카카오</td>
      <td>김진원</td>
      <td>특수관계인</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>수증, 주식분할, 단순매도</td>
    </tr>
    <tr>
      <th>3</th>
      <td>카카오</td>
      <td>김행자</td>
      <td>특수관계인</td>
      <td>0.00</td>
      <td>0.02</td>
      <td>수증, 주식분할</td>
    </tr>
    <tr>
      <th>4</th>
      <td>카카오</td>
      <td>김현수</td>
      <td>특수관계인</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>단순 매매</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>74</th>
      <td>카카오</td>
      <td>황인호</td>
      <td>특수관계인</td>
      <td>0.01</td>
      <td>0.00</td>
      <td>자사주 상여금 수취, 주식분할, 주식매수선택권 행사,특별관계해소</td>
    </tr>
    <tr>
      <th>75</th>
      <td>카카오</td>
      <td>김예빈</td>
      <td>특수관계인</td>
      <td>0.00</td>
      <td>0.06</td>
      <td>수증, 주식분할</td>
    </tr>
    <tr>
      <th>76</th>
      <td>카카오</td>
      <td>김유태</td>
      <td>특수관계인</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>수증, 주식분할</td>
    </tr>
    <tr>
      <th>77</th>
      <td>카카오</td>
      <td>계</td>
      <td>NaN</td>
      <td>25.47</td>
      <td>24.19</td>
      <td>-</td>
    </tr>
    <tr>
      <th>78</th>
      <td>카카오</td>
      <td>계</td>
      <td>NaN</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
  </tbody>
</table>
<p>79 rows × 6 columns</p>
</div>



 - 컬럼명 '관계'에서 NaN값을 없애주고, 기초지분율와 기말지분율을 숫자형으로 바꾸어 준다.

  - 그리고, 기초지분율을 내림차순으로 정렬하고, 5개만 뽑아본다.


```python
corp_code = df_listed[df_listed['corp_name'] == '카카오'].iloc[0,0]
data = dart_fss.api.info.hyslr_sttus('00258801', '2021', '11011')

df = pd.DataFrame(data['list'])
df = df[['corp_name','nm','relate','bsis_posesn_stock_qota_rt','trmend_posesn_stock_qota_rt','rm']]
df.columns = ['회사명','이름','관계','기초지분율','기말지분율','비고']

df = df[df['관계'].notnull()]

df['기초지분율'] = pd.to_numeric(df['기초지분율'])
df['기말지분율'] = pd.to_numeric(df['기말지분율'])

df.sort_values(by='기초지분율',ascending=False).head(5)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>회사명</th>
      <th>이름</th>
      <th>관계</th>
      <th>기초지분율</th>
      <th>기말지분율</th>
      <th>비고</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>카카오</td>
      <td>김범수</td>
      <td>본인</td>
      <td>14.12</td>
      <td>13.26</td>
      <td>증여 주식분할</td>
    </tr>
    <tr>
      <th>11</th>
      <td>카카오</td>
      <td>(주)케이큐브홀딩스</td>
      <td>특수관계인</td>
      <td>11.22</td>
      <td>10.55</td>
      <td>주식분할, 단순매도</td>
    </tr>
    <tr>
      <th>40</th>
      <td>카카오</td>
      <td>박승기</td>
      <td>특수관계인</td>
      <td>0.07</td>
      <td>0.00</td>
      <td>특수관계 해소</td>
    </tr>
    <tr>
      <th>74</th>
      <td>카카오</td>
      <td>황인호</td>
      <td>특수관계인</td>
      <td>0.01</td>
      <td>0.00</td>
      <td>자사주 상여금 수취, 주식분할, 주식매수선택권 행사,특별관계해소</td>
    </tr>
    <tr>
      <th>43</th>
      <td>카카오</td>
      <td>백상엽</td>
      <td>특수관계인</td>
      <td>0.01</td>
      <td>0.01</td>
      <td>주식분할</td>
    </tr>
  </tbody>
</table>
</div>



- 여러 기업을 적용시키기 위해, 함수로 만들어본다.


```python
def get_shareholders(corp_code):
  data = dart_fss.api.info.hyslr_sttus(corp_code, '2021', '11011')

  df = pd.DataFrame(data['list'])
  df = df[['corp_name','nm','relate','bsis_posesn_stock_qota_rt','trmend_posesn_stock_qota_rt','rm']]
  df.columns = ['회사명','이름','관계','기초지분율','기말지분율','비고']

  df = df[df['관계'].notnull()]

  df['기초지분율'] = pd.to_numeric(df['기초지분율'])
  df['기말지분율'] = pd.to_numeric(df['기말지분율'])

  return df.sort_values(by='기초지분율',ascending=False).head(3)

get_shareholders('00258801')   #카카오 코드
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>회사명</th>
      <th>이름</th>
      <th>관계</th>
      <th>기초지분율</th>
      <th>기말지분율</th>
      <th>비고</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>카카오</td>
      <td>김범수</td>
      <td>본인</td>
      <td>14.12</td>
      <td>13.26</td>
      <td>증여 주식분할</td>
    </tr>
    <tr>
      <th>11</th>
      <td>카카오</td>
      <td>(주)케이큐브홀딩스</td>
      <td>특수관계인</td>
      <td>11.22</td>
      <td>10.55</td>
      <td>주식분할, 단순매도</td>
    </tr>
    <tr>
      <th>40</th>
      <td>카카오</td>
      <td>박승기</td>
      <td>특수관계인</td>
      <td>0.07</td>
      <td>0.00</td>
      <td>특수관계 해소</td>
    </tr>
  </tbody>
</table>
</div>



* 상장 종목 중 10개만 추려내기
  - 전체 종목을 다 하면 매우 좋겠지만, 하루에 쓸 수 있는 Quata(한도)가 정해져 있기 때문에, 샘플 10개만 뽑아본다.
  - df_listed만 실행하면 전체 종목이 나오게 된다.

  - df_listed.sample(10) 는 실행할 때 마다 다르게 나온다.


```python
df_listed.sample(10)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>stock_code</th>
      <th>modify_date</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>66136</th>
      <td>00118008</td>
      <td>동원금속</td>
      <td>018500</td>
      <td>20220311</td>
    </tr>
    <tr>
      <th>97624</th>
      <td>00615723</td>
      <td>아이윈플러스</td>
      <td>123010</td>
      <td>20230320</td>
    </tr>
    <tr>
      <th>102310</th>
      <td>00562245</td>
      <td>태웅로직스</td>
      <td>124560</td>
      <td>20230223</td>
    </tr>
    <tr>
      <th>5699</th>
      <td>00268297</td>
      <td>에코페트로시스템</td>
      <td>042870</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>102587</th>
      <td>00422895</td>
      <td>세이브존I&amp;C</td>
      <td>067830</td>
      <td>20230421</td>
    </tr>
    <tr>
      <th>6115</th>
      <td>00347363</td>
      <td>에이치원바이오</td>
      <td>052310</td>
      <td>20170630</td>
    </tr>
    <tr>
      <th>43431</th>
      <td>01199985</td>
      <td>미래에셋대우기업인수목적1호</td>
      <td>265480</td>
      <td>20200103</td>
    </tr>
    <tr>
      <th>66140</th>
      <td>00561732</td>
      <td>아스플로</td>
      <td>159010</td>
      <td>20220603</td>
    </tr>
    <tr>
      <th>97956</th>
      <td>00410739</td>
      <td>피에이치씨</td>
      <td>057880</td>
      <td>20230306</td>
    </tr>
    <tr>
      <th>68736</th>
      <td>01399071</td>
      <td>고바이오랩</td>
      <td>348150</td>
      <td>20220802</td>
    </tr>
  </tbody>
</table>
</div>



* 10개 종목에 대해 해보기
  - 우선, 10개 종목의 코드를 출력해본다.


```python
corp_codes = list(df_listed.sample(10)['corp_code'])

corp_codes
```




    ['00557049',
     '00116073',
     '01060735',
     '01405451',
     '00156150',
     '01051092',
     '00112165',
     '00113614',
     '00505198',
     '00371519']



  - 10개 기업을 붙여서 보기


```python
corp_codes = list(df_listed.sample(10)['corp_code'])

dfs = []
for corp_code in corp_codes:
  try:
    df = get_shareholders(corp_code)
    dfs.append(df)
  except:
    print(f'error - {corp_code}')

df_result = pd.concat(dfs)
df_result
```

    error - 00154693
    error - 01602638
    




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>회사명</th>
      <th>이름</th>
      <th>관계</th>
      <th>기초지분율</th>
      <th>기말지분율</th>
      <th>비고</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>3</th>
      <td>동원개발</td>
      <td>(주)동원주택</td>
      <td>특수관계인</td>
      <td>32.51</td>
      <td>32.51</td>
      <td>-</td>
    </tr>
    <tr>
      <th>1</th>
      <td>동원개발</td>
      <td>장호익</td>
      <td>최대주주</td>
      <td>16.25</td>
      <td>16.25</td>
      <td>-</td>
    </tr>
    <tr>
      <th>4</th>
      <td>동원개발</td>
      <td>(주)동진건설산업</td>
      <td>특수관계인</td>
      <td>9.40</td>
      <td>9.40</td>
      <td>-</td>
    </tr>
    <tr>
      <th>0</th>
      <td>대신정보통신</td>
      <td>이재원</td>
      <td>본인</td>
      <td>6.83</td>
      <td>6.83</td>
      <td>-</td>
    </tr>
    <tr>
      <th>1</th>
      <td>대신정보통신</td>
      <td>양회경</td>
      <td>배우자</td>
      <td>3.44</td>
      <td>3.44</td>
      <td>-</td>
    </tr>
    <tr>
      <th>2</th>
      <td>대신정보통신</td>
      <td>양미경</td>
      <td>처형</td>
      <td>3.06</td>
      <td>3.06</td>
      <td>-</td>
    </tr>
    <tr>
      <th>0</th>
      <td>원익큐브</td>
      <td>㈜원익머트리얼즈</td>
      <td>최대주주</td>
      <td>31.57</td>
      <td>31.57</td>
      <td>-</td>
    </tr>
    <tr>
      <th>1</th>
      <td>원익큐브</td>
      <td>이용한</td>
      <td>특수관계인</td>
      <td>1.28</td>
      <td>1.28</td>
      <td>-</td>
    </tr>
    <tr>
      <th>0</th>
      <td>신한제7호기업인수목적</td>
      <td>교정공제회</td>
      <td>최대주주</td>
      <td>10.99</td>
      <td>10.99</td>
      <td>발기주주</td>
    </tr>
    <tr>
      <th>0</th>
      <td>삼아알미늄</td>
      <td>日本동양알미늄(주)</td>
      <td>본인</td>
      <td>33.40</td>
      <td>33.40</td>
      <td>-</td>
    </tr>
    <tr>
      <th>1</th>
      <td>삼아알미늄</td>
      <td>한남희</td>
      <td>발행회사 임원</td>
      <td>9.86</td>
      <td>9.86</td>
      <td>-</td>
    </tr>
    <tr>
      <th>8</th>
      <td>삼아알미늄</td>
      <td>(주)소이물산</td>
      <td>기타</td>
      <td>1.41</td>
      <td>0.91</td>
      <td>-</td>
    </tr>
    <tr>
      <th>0</th>
      <td>파마리서치</td>
      <td>정상수</td>
      <td>본인</td>
      <td>35.56</td>
      <td>35.22</td>
      <td>-</td>
    </tr>
    <tr>
      <th>1</th>
      <td>파마리서치</td>
      <td>강기석</td>
      <td>임원</td>
      <td>3.84</td>
      <td>3.80</td>
      <td>-</td>
    </tr>
    <tr>
      <th>2</th>
      <td>파마리서치</td>
      <td>백승걸</td>
      <td>임원</td>
      <td>0.50</td>
      <td>0.49</td>
      <td>-</td>
    </tr>
    <tr>
      <th>0</th>
      <td>레인보우로보틱스</td>
      <td>오준호</td>
      <td>최대주주</td>
      <td>21.50</td>
      <td>20.98</td>
      <td>주1)</td>
    </tr>
    <tr>
      <th>4</th>
      <td>레인보우로보틱스</td>
      <td>이정호</td>
      <td>등기임원</td>
      <td>8.86</td>
      <td>8.65</td>
      <td>주1)</td>
    </tr>
    <tr>
      <th>1</th>
      <td>레인보우로보틱스</td>
      <td>윤혜선</td>
      <td>배우자</td>
      <td>6.85</td>
      <td>6.69</td>
      <td>주1)</td>
    </tr>
    <tr>
      <th>0</th>
      <td>에이디엠코리아</td>
      <td>모비스</td>
      <td>본인</td>
      <td>43.17</td>
      <td>34.91</td>
      <td>유상증자등으로 인한 지분율변동</td>
    </tr>
  </tbody>
</table>
</div>



* 조건을 추가하기
  - 증감이 큰 순서대로 정렬하기 (여기서 sample(10)을 지우면, 전체 데이터 정렬을 볼 수 있는 것이다.)


```python
corp_codes = list(df_listed.sample(10)['corp_code'])

dfs = []
for corp_code in corp_codes:
  try:
    df = get_shareholders(corp_code)
    dfs.append(df)
  except:
    print(f'error - {corp_code}')

df_result = pd.concat(dfs)

df_result['증감'] = df_result['기말지분율'] - df_result['기초지분율']

df_result.sort_values(by='증감',ascending=False)
```

    error - 01667592
    




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>회사명</th>
      <th>이름</th>
      <th>관계</th>
      <th>기초지분율</th>
      <th>기말지분율</th>
      <th>비고</th>
      <th>증감</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>4</th>
      <td>에너토크</td>
      <td>한우리나눔재단</td>
      <td>주주</td>
      <td>5.00</td>
      <td>9.48</td>
      <td>-</td>
      <td>4.48</td>
    </tr>
    <tr>
      <th>0</th>
      <td>마크로젠</td>
      <td>서정선</td>
      <td>최대주주 본인</td>
      <td>8.53</td>
      <td>9.54</td>
      <td>-</td>
      <td>1.01</td>
    </tr>
    <tr>
      <th>0</th>
      <td>에너토크</td>
      <td>서부전기(주)</td>
      <td>본인</td>
      <td>11.91</td>
      <td>11.91</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>1</th>
      <td>넥스쳐</td>
      <td>(주)아이템베이</td>
      <td>특수관계인</td>
      <td>0.36</td>
      <td>0.36</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>0</th>
      <td>넥스쳐</td>
      <td>(주)모다</td>
      <td>본인</td>
      <td>48.54</td>
      <td>48.54</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>0</th>
      <td>디지틀조선</td>
      <td>방상훈</td>
      <td>최대주주\n(본인)</td>
      <td>3.95</td>
      <td>3.95</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>5</th>
      <td>디지틀조선</td>
      <td>(주)스포츠조선</td>
      <td>계열사</td>
      <td>6.05</td>
      <td>6.05</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>6</th>
      <td>디지틀조선</td>
      <td>(주)일광</td>
      <td>계열사</td>
      <td>7.59</td>
      <td>7.59</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>2</th>
      <td>이퓨쳐</td>
      <td>한상호</td>
      <td>임 원\n(이사)</td>
      <td>0.26</td>
      <td>0.26</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>1</th>
      <td>이퓨쳐</td>
      <td>김경숙</td>
      <td>임 원\n(이사)</td>
      <td>3.94</td>
      <td>3.94</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>0</th>
      <td>이퓨쳐</td>
      <td>이기현</td>
      <td>본 인\n(대표이사)</td>
      <td>24.28</td>
      <td>24.28</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>2</th>
      <td>텔코웨어</td>
      <td>신승호</td>
      <td>임원</td>
      <td>1.69</td>
      <td>1.69</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>1</th>
      <td>텔코웨어</td>
      <td>텔코인(주)</td>
      <td>계열사</td>
      <td>6.14</td>
      <td>6.14</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>0</th>
      <td>텔코웨어</td>
      <td>금한태</td>
      <td>본인</td>
      <td>21.36</td>
      <td>21.36</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>0</th>
      <td>새론오토모티브</td>
      <td>Nisshinbo\nHoldings INC</td>
      <td>본인</td>
      <td>65.00</td>
      <td>65.00</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>0</th>
      <td>대신밸런스제10호기업인수목적</td>
      <td>뉴젠인베스트먼트(주)</td>
      <td>본인</td>
      <td>7.33</td>
      <td>7.33</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>2</th>
      <td>넥스쳐</td>
      <td>(주)아이엠아이</td>
      <td>특수관계인</td>
      <td>0.36</td>
      <td>0.36</td>
      <td>-</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>3</th>
      <td>와이아이케이</td>
      <td>엑시콘</td>
      <td>관계회사</td>
      <td>0.29</td>
      <td>0.28</td>
      <td>-</td>
      <td>-0.01</td>
    </tr>
    <tr>
      <th>4</th>
      <td>마크로젠</td>
      <td>서수현</td>
      <td>최대주주의 자</td>
      <td>0.63</td>
      <td>0.62</td>
      <td>-</td>
      <td>-0.01</td>
    </tr>
    <tr>
      <th>3</th>
      <td>마크로젠</td>
      <td>이은화</td>
      <td>최대주주의 배우자</td>
      <td>0.71</td>
      <td>0.70</td>
      <td>-</td>
      <td>-0.01</td>
    </tr>
    <tr>
      <th>0</th>
      <td>와이아이케이</td>
      <td>(주)샘텍</td>
      <td>최대주주</td>
      <td>51.33</td>
      <td>50.01</td>
      <td>교환권청구</td>
      <td>-1.32</td>
    </tr>
    <tr>
      <th>1</th>
      <td>에너토크</td>
      <td>장덕인</td>
      <td>당사임원</td>
      <td>3.52</td>
      <td>0.62</td>
      <td>-</td>
      <td>-2.90</td>
    </tr>
    <tr>
      <th>2</th>
      <td>와이아이케이</td>
      <td>디에이치케이솔루션(주)</td>
      <td>관계회사</td>
      <td>4.43</td>
      <td>1.52</td>
      <td>-</td>
      <td>-2.91</td>
    </tr>
  </tbody>
</table>
</div>



* 한 종목에 대해 해보기
  - 기업의 재무정보 가져오기


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.finance.fnltt_singl_acnt(corp_code, '2021', '11011')

df = pd.DataFrame(data['list'])
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>reprt_code</th>
      <th>bsns_year</th>
      <th>corp_code</th>
      <th>stock_code</th>
      <th>fs_div</th>
      <th>fs_nm</th>
      <th>sj_div</th>
      <th>sj_nm</th>
      <th>account_nm</th>
      <th>...</th>
      <th>thstrm_dt</th>
      <th>thstrm_amount</th>
      <th>frmtrm_nm</th>
      <th>frmtrm_dt</th>
      <th>frmtrm_amount</th>
      <th>bfefrmtrm_nm</th>
      <th>bfefrmtrm_dt</th>
      <th>bfefrmtrm_amount</th>
      <th>ord</th>
      <th>currency</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>유동자산</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>218,163,185,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>198,215,579,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>181,385,260,000,000</td>
      <td>1</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>비유동자산</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>208,457,973,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>180,020,139,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>171,179,237,000,000</td>
      <td>3</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>자산총계</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>426,621,158,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>378,235,718,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>352,564,497,000,000</td>
      <td>5</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>유동부채</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>88,117,133,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>75,604,351,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>63,782,764,000,000</td>
      <td>7</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>비유동부채</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>33,604,094,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>26,683,351,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>25,901,312,000,000</td>
      <td>9</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>5</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>부채총계</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>121,721,227,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>102,287,702,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>89,684,076,000,000</td>
      <td>11</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>6</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>자본금</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>897,514,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>897,514,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>897,514,000,000</td>
      <td>13</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>7</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>이익잉여금</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>293,064,763,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>271,068,211,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>254,582,894,000,000</td>
      <td>17</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>8</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>자본총계</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>304,899,931,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>275,948,016,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>262,880,421,000,000</td>
      <td>21</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>9</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>매출액</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>279,604,799,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>236,806,988,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>230,400,881,000,000</td>
      <td>23</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>10</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>영업이익</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>51,633,856,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>35,993,876,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>27,768,509,000,000</td>
      <td>25</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>11</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>법인세차감전 순이익</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>53,351,827,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>36,345,117,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>30,432,189,000,000</td>
      <td>27</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>12</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>당기순이익</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>39,907,450,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>26,407,832,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>21,738,865,000,000</td>
      <td>29</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>13</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>당기순이익(손실)</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>39,907,450,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>26,407,832,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>21,738,865,000,000</td>
      <td>61</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>14</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>유동자산</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>73,553,416,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>73,798,549,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>72,659,080,000,000</td>
      <td>2</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>15</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>비유동자산</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>177,558,768,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>155,865,878,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>143,521,840,000,000</td>
      <td>4</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>16</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>자산총계</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>251,112,184,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>229,664,427,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>216,180,920,000,000</td>
      <td>6</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>17</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>유동부채</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>53,067,303,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>44,412,904,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>36,237,164,000,000</td>
      <td>8</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>18</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>비유동부채</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>4,851,149,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>1,934,799,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>2,073,509,000,000</td>
      <td>10</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>19</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>부채총계</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>57,918,452,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>46,347,703,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>38,310,673,000,000</td>
      <td>12</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>20</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>자본금</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>897,514,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>897,514,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>897,514,000,000</td>
      <td>15</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>21</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>이익잉여금</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>188,774,335,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>178,284,102,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>172,288,326,000,000</td>
      <td>19</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>22</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>자본총계</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>193,193,732,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>183,316,724,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>177,870,247,000,000</td>
      <td>22</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>23</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>매출액</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>199,744,705,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>166,311,191,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>154,772,859,000,000</td>
      <td>24</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>24</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>영업이익</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>31,993,162,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>20,518,974,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>14,115,067,000,000</td>
      <td>26</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>25</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>법인세차감전 순이익</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>38,704,492,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>20,451,923,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>19,032,469,000,000</td>
      <td>28</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>26</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>당기순이익</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>30,970,954,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>15,615,018,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>15,353,323,000,000</td>
      <td>30</td>
      <td>KRW</td>
    </tr>
    <tr>
      <th>27</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>OFS</td>
      <td>재무제표</td>
      <td>IS</td>
      <td>손익계산서</td>
      <td>당기순이익(손실)</td>
      <td>...</td>
      <td>2021.01.01 ~ 2021.12.31</td>
      <td>30,970,954,000,000</td>
      <td>제 52 기</td>
      <td>2020.01.01 ~ 2020.12.31</td>
      <td>15,615,018,000,000</td>
      <td>제 51 기</td>
      <td>2019.01.01 ~ 2019.12.31</td>
      <td>15,353,323,000,000</td>
      <td>62</td>
      <td>KRW</td>
    </tr>
  </tbody>
</table>
<p>28 rows × 21 columns</p>
</div>



* 한 종목에 대해 표 그리기

  - 조건을 충족하는 데이터프레임 만들기


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.finance.fnltt_singl_acnt(corp_code, '2021', '11011')

df = pd.DataFrame(data['list'])

cond = (df['fs_div'] == 'CFS') & (df['account_nm'] == '이익잉여금')
df = df[cond]
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>reprt_code</th>
      <th>bsns_year</th>
      <th>corp_code</th>
      <th>stock_code</th>
      <th>fs_div</th>
      <th>fs_nm</th>
      <th>sj_div</th>
      <th>sj_nm</th>
      <th>account_nm</th>
      <th>...</th>
      <th>thstrm_dt</th>
      <th>thstrm_amount</th>
      <th>frmtrm_nm</th>
      <th>frmtrm_dt</th>
      <th>frmtrm_amount</th>
      <th>bfefrmtrm_nm</th>
      <th>bfefrmtrm_dt</th>
      <th>bfefrmtrm_amount</th>
      <th>ord</th>
      <th>currency</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>7</th>
      <td>20220308000798</td>
      <td>11011</td>
      <td>2021</td>
      <td>00126380</td>
      <td>005930</td>
      <td>CFS</td>
      <td>연결재무제표</td>
      <td>BS</td>
      <td>재무상태표</td>
      <td>이익잉여금</td>
      <td>...</td>
      <td>2021.12.31 현재</td>
      <td>293,064,763,000,000</td>
      <td>제 52 기</td>
      <td>2020.12.31 현재</td>
      <td>271,068,211,000,000</td>
      <td>제 51 기</td>
      <td>2019.12.31 현재</td>
      <td>254,582,894,000,000</td>
      <td>17</td>
      <td>KRW</td>
    </tr>
  </tbody>
</table>
<p>1 rows × 21 columns</p>
</div>



  - 기본 정보만 가지고 df 만들기


```python
corp_code = df_listed[df_listed['corp_name'] == '삼성전자'].iloc[0,0]
data = dart_fss.api.finance.fnltt_singl_acnt(corp_code, '2021', '11011')

df = pd.DataFrame(data['list'])

cond = (df['fs_div'] == 'CFS') & (df['account_nm'] == '이익잉여금')
df = df[cond]

df['name'] = '삼성전자'

df = df[['name','thstrm_amount','frmtrm_amount']]
df.columns = ['이름','당기','전기']

df['당기'] = pd.to_numeric(df['당기'].str.replace(',',''))
df['전기'] = pd.to_numeric(df['전기'].str.replace(',',''))

df['증감'] = df['당기'] - df['전기']
df['증감율'] = abs(df['증감'])/abs(df['전기'])

df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>이름</th>
      <th>당기</th>
      <th>전기</th>
      <th>증감</th>
      <th>증감율</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>7</th>
      <td>삼성전자</td>
      <td>293064763000000</td>
      <td>271068211000000</td>
      <td>21996552000000</td>
      <td>0.081148</td>
    </tr>
  </tbody>
</table>
</div>



함수로 만들어 본다.


```python
def get_profit(name):
  corp_code = df_listed[df_listed['corp_name'] == name].iloc[0,0]
  data = dart_fss.api.finance.fnltt_singl_acnt(corp_code, '2021', '11011')

  df = pd.DataFrame(data['list'])

  cond = (df['fs_div'] == 'CFS') & (df['account_nm'] == '이익잉여금')
  df = df[cond]

  df['name'] = name

  df = df[['name','thstrm_amount','frmtrm_amount']]
  df.columns = ['이름','당기','전기']

  df['당기'] = pd.to_numeric(df['당기'].str.replace(',',''))
  df['전기'] = pd.to_numeric(df['전기'].str.replace(',',''))

  df['증감'] = df['당기'] - df['전기']
  df['증감율'] = abs(df['증감'])/abs(df['전기'])

  return df

get_profit('현대자동차')
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>이름</th>
      <th>당기</th>
      <th>전기</th>
      <th>증감</th>
      <th>증감율</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>7</th>
      <td>현대자동차</td>
      <td>73167855000000</td>
      <td>68911800000000</td>
      <td>4256055000000</td>
      <td>0.061761</td>
    </tr>
  </tbody>
</table>
</div>



* 마찬가지로 상장사 중 10개를 뽑아서 진행한다.


```python
names = list(df_listed.sample(10)['corp_name'])

dfs = []
for name in names:
  try:
    df = get_profit(name)
    dfs.append(df)
  except:
    print(f'error - {name}')

df_result = pd.concat(dfs)
df_result
```

    error - 현대해상
    




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>이름</th>
      <th>당기</th>
      <th>전기</th>
      <th>증감</th>
      <th>증감율</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>7</th>
      <td>신도리코</td>
      <td>790603559192</td>
      <td>695166062839</td>
      <td>95437496353</td>
      <td>0.137287</td>
    </tr>
    <tr>
      <th>7</th>
      <td>한진중공업홀딩스</td>
      <td>39002000000</td>
      <td>-477362000000</td>
      <td>516364000000</td>
      <td>1.081703</td>
    </tr>
    <tr>
      <th>7</th>
      <td>네오위즈홀딩스</td>
      <td>365123268539</td>
      <td>299893877851</td>
      <td>65229390688</td>
      <td>0.217508</td>
    </tr>
    <tr>
      <th>7</th>
      <td>미래컴퍼니</td>
      <td>82435413534</td>
      <td>75138283089</td>
      <td>7297130445</td>
      <td>0.097116</td>
    </tr>
    <tr>
      <th>7</th>
      <td>제이엔케이히터</td>
      <td>12875153274</td>
      <td>9664403258</td>
      <td>3210750016</td>
      <td>0.332224</td>
    </tr>
    <tr>
      <th>7</th>
      <td>클리오</td>
      <td>93327350731</td>
      <td>85062921172</td>
      <td>8264429559</td>
      <td>0.097157</td>
    </tr>
    <tr>
      <th>7</th>
      <td>롯데정보통신</td>
      <td>110351166605</td>
      <td>90876953736</td>
      <td>19474212869</td>
      <td>0.214292</td>
    </tr>
    <tr>
      <th>7</th>
      <td>누리플랜</td>
      <td>9509831794</td>
      <td>8663941930</td>
      <td>845889864</td>
      <td>0.097633</td>
    </tr>
    <tr>
      <th>7</th>
      <td>현대미포조선</td>
      <td>1633373613000</td>
      <td>1802580418000</td>
      <td>-169206805000</td>
      <td>0.093869</td>
    </tr>
  </tbody>
</table>
</div>



 * 약간의 작업을 거쳐서 이익잉여금의 변화를 우선 표기해준다.
 [증감율을 기준으로 정렬하기]


```python
names = list(df_listed.sample(10)['corp_name'])

dfs = []
for name in names:
  try:
    df = get_profit(name)
    dfs.append(df)
  except:
    print(f'error - {name}')

df_result = pd.concat(dfs)
df_result.sort_values(by='증감율',ascending=False)
```

    error - 이앤에치
    error - 인스웨이브시스템즈
    




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>이름</th>
      <th>당기</th>
      <th>전기</th>
      <th>증감</th>
      <th>증감율</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>7</th>
      <td>GS글로벌</td>
      <td>7053470074</td>
      <td>-16978024801</td>
      <td>24031494875</td>
      <td>1.415447</td>
    </tr>
    <tr>
      <th>7</th>
      <td>티앤엘</td>
      <td>57323469714</td>
      <td>39401827319</td>
      <td>17921642395</td>
      <td>0.454843</td>
    </tr>
    <tr>
      <th>7</th>
      <td>코미팜</td>
      <td>-18290372571</td>
      <td>-13831018470</td>
      <td>-4459354101</td>
      <td>0.322417</td>
    </tr>
    <tr>
      <th>6</th>
      <td>엔케이</td>
      <td>-37093120063</td>
      <td>-48255075345</td>
      <td>11161955282</td>
      <td>0.231312</td>
    </tr>
    <tr>
      <th>7</th>
      <td>오션브릿지</td>
      <td>61327843760</td>
      <td>51164096273</td>
      <td>10163747487</td>
      <td>0.198650</td>
    </tr>
    <tr>
      <th>7</th>
      <td>한미약품</td>
      <td>396915857788</td>
      <td>334116705316</td>
      <td>62799152472</td>
      <td>0.187956</td>
    </tr>
    <tr>
      <th>7</th>
      <td>삼보판지</td>
      <td>432671312556</td>
      <td>382220235354</td>
      <td>50451077202</td>
      <td>0.131995</td>
    </tr>
    <tr>
      <th>7</th>
      <td>넥스턴바이오</td>
      <td>46734495056</td>
      <td>51340910784</td>
      <td>-4606415728</td>
      <td>0.089722</td>
    </tr>
  </tbody>
</table>
</div>



 * 남녀 평균 급여 차이가 가장 안나는 회사 찾아보기


```python
def get_salary(name):
  data = dart_fss.api. info. emp_sttus(corp_code, '2021', '11011')

  df = pd.DataFrame(data['list'])
  df = df[['corp_name','sexdstn','jan_salary_am']]

  df_result = pd.DataFrame()
  doc = {
    '기업명' :df.iloc[0,0],
    '연봉(남)':df[df['sexdstn'] == '남'].iloc[0,2],
    '연봉(여)':df[df['sexdstn'] == '여'].iloc[0,2]
  }
  df_result = df_result.append(doc,ignore_index=True)

  df_result['연봉(남)'] = pd.to_numeric(df_result['연봉(남)'].str.replace(',',''))
  df_result['연봉(여)'] = pd.to_numeric(df_result['연봉(여)'].str.replace(',',''))

  return df_result

get_salary('삼성전자')
```

    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\3687614398.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc,ignore_index=True)
    




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>기업명</th>
      <th>연봉(남)</th>
      <th>연봉(여)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>야놀자</td>
      <td>122000000</td>
      <td>62000000</td>
    </tr>
  </tbody>
</table>
</div>




```python

```


```python

```


```python
corp_codes = list(df_listed.sample(50)['corp_code'])

dfs = []
for corp_code in corp_codes:
  try:
    df =  get_salary(corp_code)
    dfs.append(df)
  except :
    print(f'error - {corp_code}')

df_result = pd.concat(dfs)

df_result['차이(남-여)'] = df_result['연봉(남)'] - df_result['연봉(여)']
df_result['평균'] = (df_result['연봉(남)']+df_result['연봉(여)'])/2

df_result.sort_values(by="차이(남-여)",ascending=True)
```

    error - 00264839
    

    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    

    error - 01242241
    

    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    

    error - 00557058
    error - 00921475
    

    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    

    error - 00493501
    

    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    

    error - 00161028
    error - 01685251
    error - 00721981
    

    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    

    error - 00110176
    

    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    

    error - 00334767
    

    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    

    error - 01341630
    

    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    

    error - 00162142
    error - 00269339
    

    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    

    error - 00152914
    error - 01094565
    

    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    

    error - 01063963
    

    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    C:\Users\Howard\AppData\Local\Temp\ipykernel_19648\506646205.py:13: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
      df_result = df_result.append(doc, ignore_index=True)
    




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>기업명</th>
      <th>연봉(남)</th>
      <th>연봉(여)</th>
      <th>차이(남-여)</th>
      <th>평균</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>셀피글로벌</td>
      <td>43423000</td>
      <td>47547000</td>
      <td>-4124000</td>
      <td>45485000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>유니테크노</td>
      <td>38000000</td>
      <td>37000000</td>
      <td>1000000</td>
      <td>37500000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>파미셀</td>
      <td>47000000</td>
      <td>42000000</td>
      <td>5000000</td>
      <td>44500000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>에스디시스템</td>
      <td>36054000</td>
      <td>30637000</td>
      <td>5417000</td>
      <td>33345500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>원익큐브</td>
      <td>54084000</td>
      <td>47163000</td>
      <td>6921000</td>
      <td>50623500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>연우</td>
      <td>44483000</td>
      <td>36968000</td>
      <td>7515000</td>
      <td>40725500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>성호전자</td>
      <td>38000000</td>
      <td>30000000</td>
      <td>8000000</td>
      <td>34000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>위노바</td>
      <td>37845000</td>
      <td>27963000</td>
      <td>9882000</td>
      <td>32904000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>샘표식품</td>
      <td>48753000</td>
      <td>38814000</td>
      <td>9939000</td>
      <td>43783500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>지더블유바이텍</td>
      <td>60943000</td>
      <td>50788000</td>
      <td>10155000</td>
      <td>55865500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>라온시큐어</td>
      <td>59926000</td>
      <td>48402000</td>
      <td>11524000</td>
      <td>54164000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>와이아이케이</td>
      <td>55000000</td>
      <td>43000000</td>
      <td>12000000</td>
      <td>49000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>레몬</td>
      <td>46000000</td>
      <td>34000000</td>
      <td>12000000</td>
      <td>40000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>지란지교시큐리티</td>
      <td>56936209</td>
      <td>44488240</td>
      <td>12447969</td>
      <td>50712224.5</td>
    </tr>
    <tr>
      <th>0</th>
      <td>배럴</td>
      <td>41000000</td>
      <td>28000000</td>
      <td>13000000</td>
      <td>34500000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>메타바이오메드</td>
      <td>55000000</td>
      <td>41000000</td>
      <td>14000000</td>
      <td>48000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>LS네트웍스</td>
      <td>57000000</td>
      <td>43000000</td>
      <td>14000000</td>
      <td>50000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>유비쿼스홀딩스</td>
      <td>64514000</td>
      <td>50430000</td>
      <td>14084000</td>
      <td>57472000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>휴니드테크놀러지스</td>
      <td>56411000</td>
      <td>41209000</td>
      <td>15202000</td>
      <td>48810000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>스마트솔루션즈</td>
      <td>46489000</td>
      <td>30584000</td>
      <td>15905000</td>
      <td>38536500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>NAVER</td>
      <td>135883000</td>
      <td>117418000</td>
      <td>18465000</td>
      <td>126650500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>유아이엘</td>
      <td>46000000</td>
      <td>26000000</td>
      <td>20000000</td>
      <td>36000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>케이탑리츠</td>
      <td>68590359</td>
      <td>47905065</td>
      <td>20685294</td>
      <td>58247712.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>비츠로셀</td>
      <td>56000000</td>
      <td>34000000</td>
      <td>22000000</td>
      <td>45000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>원익</td>
      <td>63823000</td>
      <td>41623000</td>
      <td>22200000</td>
      <td>52723000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>아즈텍WB</td>
      <td>51477563</td>
      <td>27888856</td>
      <td>23588707</td>
      <td>39683209.5</td>
    </tr>
    <tr>
      <th>0</th>
      <td>오리엔탈정공</td>
      <td>60860145</td>
      <td>36862951</td>
      <td>23997194</td>
      <td>48861548.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>고려제강</td>
      <td>56000000</td>
      <td>32000000</td>
      <td>24000000</td>
      <td>44000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>무진메디</td>
      <td>61235000</td>
      <td>34903000</td>
      <td>26332000</td>
      <td>48069000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>핌스</td>
      <td>66483000</td>
      <td>39241000</td>
      <td>27242000</td>
      <td>52862000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>한농화성</td>
      <td>77106000</td>
      <td>41035000</td>
      <td>36071000</td>
      <td>59070500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>백금T&amp;A</td>
      <td>88000000</td>
      <td>42000000</td>
      <td>46000000</td>
      <td>65000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>종근당홀딩스</td>
      <td>135000000</td>
      <td>60000000</td>
      <td>75000000</td>
      <td>97500000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>진원생명과학</td>
      <td>148000000</td>
      <td>51000000</td>
      <td>97000000</td>
      <td>99500000.0</td>
    </tr>
  </tbody>
</table>
</div>



* 비상장 종목 분석하기
[비상장주식 배당정보 가져오기]


```python
corp_code = df_non_listed[df_non_listed['corp_name'] == '야놀자'].iloc[0,0]
data = dart_fss.api.info.alot_matter(corp_code, '2021', '11011')
df = pd.DataFrame(data['list'])

df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rcept_no</th>
      <th>corp_cls</th>
      <th>corp_code</th>
      <th>corp_name</th>
      <th>se</th>
      <th>thstrm</th>
      <th>frmtrm</th>
      <th>lwfr</th>
      <th>stock_knd</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>주당액면가액(원)</td>
      <td>500</td>
      <td>500</td>
      <td>5,000</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>(연결)당기순이익(백만원)</td>
      <td>45,972</td>
      <td>-65,696</td>
      <td>-66,761</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>(별도)당기순이익(백만원)</td>
      <td>32,927</td>
      <td>-63,823</td>
      <td>-75,894</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>(연결)주당순이익(원)</td>
      <td>565</td>
      <td>-1,196</td>
      <td>-25,340</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>현금배당금총액(백만원)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>5</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>주식배당금총액(백만원)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>6</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>(연결)현금배당성향(%)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>7</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>현금배당수익률(%)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>보통주</td>
    </tr>
    <tr>
      <th>8</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>현금배당수익률(%)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>우선주</td>
    </tr>
    <tr>
      <th>9</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>주식배당수익률(%)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>보통주</td>
    </tr>
    <tr>
      <th>10</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>주식배당수익률(%)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>우선주</td>
    </tr>
    <tr>
      <th>11</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>주당 현금배당금(원)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>보통주</td>
    </tr>
    <tr>
      <th>12</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>주당 현금배당금(원)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>우선주</td>
    </tr>
    <tr>
      <th>13</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>주당 주식배당(주)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>보통주</td>
    </tr>
    <tr>
      <th>14</th>
      <td>20220331003744</td>
      <td>E</td>
      <td>00907864</td>
      <td>야놀자</td>
      <td>주당 주식배당(주)</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>우선주</td>
    </tr>
  </tbody>
</table>
</div>



 - 배당 정보 다듬기
 [데이터 표로 만들기]


```python
corp_code = df_non_listed[df_non_listed['corp_name'] == '야놀자'].iloc[0,0]
data = dart_fss.api.info.alot_matter(corp_code, '2021', '11011')
df = pd.DataFrame(data['list'])

df = df[df['se'] == '(연결)당기순이익(백만원)'][['corp_name','thstrm','frmtrm','lwfr']]
df.columns = ['기업명','2021','2020','2019']
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>기업명</th>
      <th>2021</th>
      <th>2020</th>
      <th>2019</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>야놀자</td>
      <td>45,972</td>
      <td>-65,696</td>
      <td>-66,761</td>
    </tr>
  </tbody>
</table>
</div>



[숫자형으로 변환하기]


```python
corp_code = df_non_listed[df_non_listed['corp_name'] == '야놀자'].iloc[0,0]
data = dart_fss.api.info.alot_matter(corp_code, '2021', '11011')
df = pd.DataFrame(data['list'])

df = df[df['se'] == '(연결)당기순이익(백만원)'][['corp_name','thstrm','frmtrm','lwfr']]
df.columns = ['기업명','2021','2020','2019']

df['2021'] = pd.to_numeric(df['2021'].str.replace(',',''))
df['2020'] = pd.to_numeric(df['2020'].str.replace(',',''))
df['2019'] = pd.to_numeric(df['2019'].str.replace(',',''))

df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>기업명</th>
      <th>2021</th>
      <th>2020</th>
      <th>2019</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>야놀자</td>
      <td>45972</td>
      <td>-65696</td>
      <td>-66761</td>
    </tr>
  </tbody>
</table>
</div>



* 함수로 만들기


```python
def get_earning(name):
  corp_code = df_non_listed[df_non_listed['corp_name'] == name].iloc[0,0]
  data = dart_fss.api.info.alot_matter(corp_code, '2021', '11011')
  df = pd.DataFrame(data['list'])

  df = df[df['se'] == '(연결)당기순이익(백만원)'][['corp_name','thstrm','frmtrm','lwfr']]
  df.columns = ['기업명','2021','2020','2019']

  return df

get_earning('비바리퍼블리카')
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>기업명</th>
      <th>2021</th>
      <th>2020</th>
      <th>2019</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>비바리퍼블리카</td>
      <td>-215,364</td>
      <td>-90,953</td>
      <td>-124,407</td>
    </tr>
  </tbody>
</table>
</div>



* 여러 종목 해보기

  - 할 수는 있지만, 비상장종목은 특히 정보가 없는 경우가 많다.


```python
names = list(df_non_listed.sample(20) ['corp_name'])
dfs = []
for name in names:
  try:
    df = get_earning(name)
    dfs.append(df)
  except :
    print(f'error - {name}')

#df_result = pd.concat(dfs)
df_result
```

    error - 피엔씨
    error - 영우특수강
    error - 도시환경종합건축사사무소
    error - 비와이디코리아
    error - ProjectGuardianHoldingsLimited
    error - 힉스멤버스
    error - 에이원제일차
    error - 티유제일차
    error - 엘엑스컴퍼니
    error - 대전열병합발전
    error - 에스에이파트너스
    error - 동호건설
    error - 협성섬유
    error - 은진물류
    error - 액세스리미티드
    error - 항상위드
    error - 국제그라비아
    error - 랩소프트
    error - 서원케미칼
    error - 테라핀
    




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>기업명</th>
      <th>연봉(남)</th>
      <th>연봉(여)</th>
      <th>차이(남-여)</th>
      <th>평균</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>오리엔탈정공</td>
      <td>60860145</td>
      <td>36862951</td>
      <td>23997194</td>
      <td>48861548.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>레몬</td>
      <td>46000000</td>
      <td>34000000</td>
      <td>12000000</td>
      <td>40000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>종근당홀딩스</td>
      <td>135000000</td>
      <td>60000000</td>
      <td>75000000</td>
      <td>97500000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>샘표식품</td>
      <td>48753000</td>
      <td>38814000</td>
      <td>9939000</td>
      <td>43783500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>파미셀</td>
      <td>47000000</td>
      <td>42000000</td>
      <td>5000000</td>
      <td>44500000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>지란지교시큐리티</td>
      <td>56936209</td>
      <td>44488240</td>
      <td>12447969</td>
      <td>50712224.5</td>
    </tr>
    <tr>
      <th>0</th>
      <td>위노바</td>
      <td>37845000</td>
      <td>27963000</td>
      <td>9882000</td>
      <td>32904000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>무진메디</td>
      <td>61235000</td>
      <td>34903000</td>
      <td>26332000</td>
      <td>48069000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>비츠로셀</td>
      <td>56000000</td>
      <td>34000000</td>
      <td>22000000</td>
      <td>45000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>에스디시스템</td>
      <td>36054000</td>
      <td>30637000</td>
      <td>5417000</td>
      <td>33345500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>셀피글로벌</td>
      <td>43423000</td>
      <td>47547000</td>
      <td>-4124000</td>
      <td>45485000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>케이탑리츠</td>
      <td>68590359</td>
      <td>47905065</td>
      <td>20685294</td>
      <td>58247712.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>지더블유바이텍</td>
      <td>60943000</td>
      <td>50788000</td>
      <td>10155000</td>
      <td>55865500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>유아이엘</td>
      <td>46000000</td>
      <td>26000000</td>
      <td>20000000</td>
      <td>36000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>연우</td>
      <td>44483000</td>
      <td>36968000</td>
      <td>7515000</td>
      <td>40725500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>배럴</td>
      <td>41000000</td>
      <td>28000000</td>
      <td>13000000</td>
      <td>34500000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>NAVER</td>
      <td>135883000</td>
      <td>117418000</td>
      <td>18465000</td>
      <td>126650500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>성호전자</td>
      <td>38000000</td>
      <td>30000000</td>
      <td>8000000</td>
      <td>34000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>유비쿼스홀딩스</td>
      <td>64514000</td>
      <td>50430000</td>
      <td>14084000</td>
      <td>57472000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>메타바이오메드</td>
      <td>55000000</td>
      <td>41000000</td>
      <td>14000000</td>
      <td>48000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>휴니드테크놀러지스</td>
      <td>56411000</td>
      <td>41209000</td>
      <td>15202000</td>
      <td>48810000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>스마트솔루션즈</td>
      <td>46489000</td>
      <td>30584000</td>
      <td>15905000</td>
      <td>38536500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>핌스</td>
      <td>66483000</td>
      <td>39241000</td>
      <td>27242000</td>
      <td>52862000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>아즈텍WB</td>
      <td>51477563</td>
      <td>27888856</td>
      <td>23588707</td>
      <td>39683209.5</td>
    </tr>
    <tr>
      <th>0</th>
      <td>원익</td>
      <td>63823000</td>
      <td>41623000</td>
      <td>22200000</td>
      <td>52723000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>백금T&amp;A</td>
      <td>88000000</td>
      <td>42000000</td>
      <td>46000000</td>
      <td>65000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>진원생명과학</td>
      <td>148000000</td>
      <td>51000000</td>
      <td>97000000</td>
      <td>99500000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>라온시큐어</td>
      <td>59926000</td>
      <td>48402000</td>
      <td>11524000</td>
      <td>54164000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>LS네트웍스</td>
      <td>57000000</td>
      <td>43000000</td>
      <td>14000000</td>
      <td>50000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>유니테크노</td>
      <td>38000000</td>
      <td>37000000</td>
      <td>1000000</td>
      <td>37500000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>원익큐브</td>
      <td>54084000</td>
      <td>47163000</td>
      <td>6921000</td>
      <td>50623500.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>와이아이케이</td>
      <td>55000000</td>
      <td>43000000</td>
      <td>12000000</td>
      <td>49000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>고려제강</td>
      <td>56000000</td>
      <td>32000000</td>
      <td>24000000</td>
      <td>44000000.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>한농화성</td>
      <td>77106000</td>
      <td>41035000</td>
      <td>36071000</td>
      <td>59070500.0</td>
    </tr>
  </tbody>
</table>
</div>




```python

```


```python

```


```python

```


```python

```


```python

```


```python

```
