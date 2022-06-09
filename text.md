# Abstract
[担当：山下]
The Swarm mission was selected as the 5th mission in ESA's Earth Explorer Programme in 2004.
スウォーム（これは欧州宇宙機関(ESA)が2013年11月に打ち上げた地磁気観測衛星。同型の衛星3基が連携して観測を行い、地球磁気圏のデータを収集する。）ミッションは、2004年にESAのアースエクスプローラープログラム(地球冒険プログラム)の5番目のミッションとして選ばれました。

This mission aims at measuring the Earth's magnetic field with unprecedented accuracy.
このミッションは、これまでにない精度(正確さ)で地球の磁場を測定することを目的としています。

This will be done by a constellation of three satellites, where two will fly at lower altitude, measuring the gradient of the magnetic field, and one satellite will fly at higher altitude.
これは、３つの衛星の集まりによって行われ、2つは低高度で飛行し、磁場の勾配を測定し、1つの衛星は高高度で飛行します。

The measured magnetic field is the sum of many contributions including both magnetic fields and currents in the Earth's interior and electrical currents in Geospace.
測定された磁場は、地球内部の磁場と電流、およびジオスペース（地球の外側で地球の近くあたり）の電流の両方を含む、多くの寄与の合計です。

In order to separate all these sources electric field and plasma measurements will also be made to complement the primary magnetic field measurements.
これらすべての寄与のもとを分離するために、１回目の磁場測定を補完するために電場とプラズマの測定も行われます。
Together these will allow the deduction of information on a series of solid earth processes responsible for the creation of the fields measured.
これらを組み合わせることで、測定されたフィールドの作成の原因になる、一連の固体地球プロセス（固体地球という学問があるらしい。）に関する情報の推定が可能になります。
 The completeness of the measurements on each satellite and the constellation aspect, however, implies simultaneous observations of a unique set of important electrodynamical parameters crucial for the understanding of the physical processes in Geospace, which are an important part of the objectives of the International Living With a Star Programme, ILWS.

ただし、各衛星の測定とその配置の完全性は、ILWS（International Living With a Star Programme。恒星と一緒に海外に住む？）の目的の重要な部分である、地理空間の物理的プロセスの理解に不可欠な重要な電気力学的パラメータの一意のセットを同時に観測することを含みます。
In this paper an overview of the Swarm science objectives, the mission concept, the scientific instrumentation, and the expected contribution to the ILWS programme will be summarized.
この論文では、スウォームの科学目的、ミッションの概念、科学機器、およびILWSプログラムへの期待される貢献の概要を要約します。

# 1. Introduction
[担当：才田]
1999年、国際測地学・地球物理学連合は今後10年間の地球の重力ポテンシャル研究を促進するために国際地磁気・高層物理学会 が提出した研究計画を採択した。そしてそれは新たな人工衛星の開発を可能にし、衛星の運用を開始しその活用が可能になった。

この国際的な地球の重力ポテンシャル研究は、1999年にオルステッド衛星が打ち上げられると同時に開始され、地球磁場観測の新たな時代を切り拓いた。このとき、20年前から走っていたMAGDSATミッションによる研究活動が同時に走っていた。
CHAMPやSAC-Cなどの衛星が2000年に追加で打ち上げられ、この研究期間の最初の1年間により精度の高い地球磁場を提供できたことによって研究はさらに発展していった。

[担当：山下]
However, these three missions were conceived as single-satellite missions.
ただし、これら3つのミッションは、単一衛星ミッションとして考案されました。

Although some of the primary instruments were similar, they all had additional different instrumentation, spacecraft designs and orbits.
主要な計器のいくつかは類似していましたが、それらはすべて、追加の異なる計器、宇宙船の設計、および軌道を持っていました。

The science results obtained from these missions demonstrate that the main limiting factor in the accuracy of present geomagnetic field models is the continuously varying contributions from external currents.
これらのミッションから得られた科学的結果は、現在の地磁気モデルの精度における主な制限要因が、外部電流からの継続的に変化する寄与であることを示しています。

Single-satellite missions are therefore not able to take advantage of the impressive instrument improvement, which has been achieved during the last couple of years.
したがって、単一衛星ミッションは、過去数年間に達成された印象的な機器の改善を利用することができません。

Multiple satellite missions measuring simultaneously over different regions of the Earth offer the only way to take full advantage of this new generation of instruments.
地球のさまざまな地域で同時に測定する複数の衛星ミッションは、この新世代の機器を最大限に活用する唯一の方法を提供します。

At the same time magnetic field measurements are important for Space Weather applications.
同時に、磁場測定は宇宙天気アプリケーションにとって重要です。

Results of combining Ørsted, CHAMP and SAC-C observations from a few suitable periods indicate the great potential of a constellation.
いくつかの適切な期間からのØrsted、CHAMP、およびSAC-Cの観測を組み合わせた結果は、衛星の配置の大きな可能性を示しています。

Ørsted：磁場を測る衛星
CHAMP：重力を測る衛星
SAC-C：カメラを乗せた衛星

[担当：山本]
Another limiting factor regarding the advance of geomagnetic research concerns the requirement for measurements during a full solar cycle.
地磁気研究の進歩に関するもう一つの制限要因は、完全な太陽周期中の測定の要件に関するものです。
This is needed to properly distinguish between solar activity and secular variation
これは、太陽活動と永年変化の影響を適切に区別するために必要です。

[担当：才田]
Scientists in the various geomagnetic research disciplines are exploring the available data with increasingly sophisticated methods.
様々な地磁気研究分野の科学者達が入手可能なデータを探しており、その手法は高度に洗練されつつある。

But continued scientific progress calls for an interdisciplinary approach based on the development of new tools to deal with all the various contributions, from the magnetosphere to the deep core, in a comprehensive way.
しかしながら科学の進歩は、地球磁気圏から地球深層部における様々な観測データの提供を可能にする新しい包括的なツールの開発と、そのツールを使った分野横断的なアプローチを要請している。

Only by such an approach we can hope to synthesise various scientific issues into a coherent and unified picture of the coupled Sun–Earth system.
そのようなアプローチによって、我々は様々な研究課題を太陽―地球連結システムの中に投影して取り組むことを期待できる。

[担当：山下]
The Swarm mission is based on the mission proposal in response to the ESA Earth Observation Programme call for Opportunity Mission proposals in 2001. The proposal was co-written and submitted by a team lead by Eigil Friis-Christensen, Hermann Lühr, and Gauthier Hulot.
スウォームミッションは、ESA地球観測プログラムからのOpportunity Mission proposals（機会ミッション提案）への要請に応じたミッション提案に基づいています。この提案は、Eigil Friis-Christensen、HermannLühr、およびGauthierHulotが率いるチームによって共同で作成および提出されました。

Out of 25 full proposals Swarm was selected as one of the three mission candidates chosen for feasibility study.
25の完全な提案の中から、スウォームが実現可能性調査のために選ばれた3つのミッション候補の1つとして選ばれました。

フェーズAの研究は、2004年の初めまでに終了し、最終的なミッション選択の基礎を形成しました（ESA SP-1279（6）、2004）。
2004年5月、スウォームミッションは、2010年に開始されるESAのリビングプラネットプログラムの5番目のアースエクスプローラーミッションとして選ばれました。
  図1は、フェーズAの産業試験コンソーシアムによって提案された宇宙船の設計を示しています。

[担当：山本]
The geomagnetic field is one of the primary factors controlling the impact on the Earth's environment of solar variations.
地磁気は、太陽変動が地球の環境に与える影響を制御する主要な要因の1つです。

Due to its focused goal and complete instrumentation to pursue this goal the Swarm mission therefore fits well into the research programme of the International Living with a Star (ILWS) program.
その焦点を絞った目標とこの目標を追求するための完全な計装により、Swarmミッションは、International Living with a Star（ILWS）プログラムの研究プログラムにうまく適合します。

ILWS was formed to stimulate, strengthen, and coordinate space research to understand the governing processes in the connected Sun-Earth system viewed as an integrated entity.
ILWSは、宇宙研究を刺激、強化、調整して、統合された実在物と見なされる接続された太陽地球システムの管理プロセスを理解するために設立されました。

The steering committee of the ILWS programme consists of members from the Canadian, Russian, Japanese, European, and  American space agencies.
ILWSプログラムの運営委員会は、カナダ、ロシア、日本、ヨーロッパ、およびアメリカの宇宙機関のメンバーで構成されています。

Its Ionosphere-Thermosphere  task group identified Swarm as an ILWS priority at a meeting held at Nice, France in April of 2003.
その電離層-熱圏タスクグループは、2003年4月にフランスのニースで開催された会議でSwarmをILWSの優先事項として特定しました。

# 2. Science Objectives
[担当：才田]
The objective of the Swarm mission is to provide the best ever survey of the geomagnetic field and its temporal evolution, in order to gain new insights into the Earth system by improving our understanding of the Earth’s interior and the Geospace environment including the Sun–Earth connection processes.
SWARMミッションの目的は地球磁場とその時間変化について過去最高の水準で調査を実施することで、それは地球内部と太陽と地球の相互作用過程を含むジオスペース（地球近傍の宇宙空間）への理解をより深め地球という一つの系に対する新しい観点をもたらす。

[担当：山下]
The Swarm mission will provide the first global representation of the geomagnetic field variations on time scales from an hour to several years.
スウォームミッションは、1時間から数年までの時間スケールでの地磁気変動の最初の世界的な表現を提供します。
The more challenging partis, however, to separate the contributions from the various sources.
ただし、より困難な部分は、さまざまな成分を分離することです。
Swarm will simultaneously obtain a space–time characterization of both the internal field sources in the Earth and the ionospheric–magnetospheric current systems.
Swarmは、地球の内部電界源と電離層-磁気圏電流システムの両方の時空間特性を同時に取得します。

[担当:山本]
The primary research objectives of the mission are:
ミッションの主な研究目的は次のとおりです。
• studies of core dynamics, geodynamo processes, and core-mantle interaction,
コアダイナミクス、ジオダイナモ(地磁気ダイナモ?)プロセス、コア-マントル相互作用の研究、
• mapping of the lithospheric magnetisation and its geo logical interpretation,
リソスフェア磁化のマッピングとその地質学的解釈、
• determination of the 3D electrical conductivity of the mantle,
マントルの3D電気伝導率の決定、
• investigation of electric currents flowing in the magneto-sphere and ionosphere
磁気圏と電離層を流れる電流の調査
