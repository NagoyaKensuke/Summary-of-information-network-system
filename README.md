# Summary-of-information-network-system
#Learning about networks and research summary

回線利用率は回線容量に比べ，実際に流れるデータ量がどれ程か割合を示す値。伝送速度×伝送効率×回線利用率＝実質の伝送速度 <br>
kbps×％×％＝kbps が実質伝送速度




Mid_report
OSI参照モデルとTCP/IPモデルの特徴の比較


OSI参照モデル(OSI reference mode)
OSI参照モデルは、ネットワークシステムの概念を7つの層に階層化したものだ。国際標準化機構（International Organization for Standardization）によって策定された。
上位の7層に近いほど人間に近いアプリケーション通信プロコトルを扱い、下位の1層に近いほど機械に近い信号のプロコトルを扱う。
上位層から順に、第7層「アプリケーション層」、第6層「プレゼンテーション層」、第5層「セッション層」、第4層「トランスポート層」、
第3層「ネットワーク層」、第2層「データリンク層」、第1層「物理層」がある。第7層から第5層が上位層で、第4層から第1層が下位層だ。
各階層間のインターフェース及びプロトコルを定義すれば、各階層に属するプロコトルや実装方法等が他の改装のプロコトルに影響されない。

TCP/IP(Transmission Control Protocol)
TCP/IPは、ネットワークシステムの概念を４つの層に階層化したものだ。インターネットプロトコルスイート(Internet protocol suite）とも呼ばれる。
基礎となるプロトコルがTCPとIPであることから、一般的にTCP/IPと呼ばれているが、2つのプロトコルだけではない。
上から、アプリケーション層、トランスポート層、インターネット層、ネットワークインターフェース層だ。

OSIとTCP/IPの比較
TCP/IPの基本仕様は1982年頃にはほぼ固まっており、OSI参照モデルは1984年に完成した。TCP/IPモデルとOSIモデルの層を比較すると、
TCP/IPモデルのアプリケーション層はOSIの第7層「アプリケーション層」、第6層「プレゼンテーション層」、第5層「セッション層」
を合わせたものに似ているが、TCP/IPモデルにはプレゼンテーション層やセッション層はない。TCP/IPのトランスポート層は、OSIトランスポート層と、
OSIセッション層の機能の一部を含んでいる。OSIの第1~2層がTCP/IPのネットワークインタフェース層にあたる。TCP/IPはOSIよりも実装面で現実的な仕様となっている。
普及するにあたって、一時は両者競合したこともあったが、構造がより単純で開発の進行が早かったTCP/IPに軍配が上がった。
TCP/IPは、「問題を解決するためにプロトコルをどう実装するか」という考えで設計されており、OSIモデルのようにすべてのネットワーク通信へ汎用的に機能するものではない。
OSIモデルで注意しなければならないことは、よりシンプルなアプリケーションではすべてのレイヤーが使われているわけではないということだ。
OSIの1~3層はどんなデータ通信にも必須だが、アプリケーションではモデル内の通常の上位層ではなく、何らかの独自のインターフェース層を使用することがある。
TCP/IPモデルとOSIモデルは、いずれもすべてのネットワーク通信の記述に用いられる概念モデルであり、
インターネットのすべての運用に用いられる重要なプロトコルだ。TCP/IPモデルは
、現在のインターネットアーキテクチャのモデリングと、ネットワーク上の伝送形態の基礎となっている。




参考文献と参考サイト
OSI参照モデルとTCP／IPについて 
https://ansl-blog.hatenablog.com/entry/2019/05/22/OSI%E5%8F%82%E7%85%A7%E3%83%A2%E3%83%87%E3%83%AB%E3%81%A8TCP%EF%BC%8FIP%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6

TCP/IPの絵本　(株)アンク

OSI参照モデルとTCP/IPの階層の違い
https://www.sbbit.jp/article/cont1/12099?page=2

TCP/IP vs. OSI: What’s the Difference Between the Two Models?
https://community.fs.com/blog/tcpip-vs-osi-whats-the-difference-between-the-two-models.html
© 2020 GitHub, Inc.
