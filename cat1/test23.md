<div class="col-12 col-sm-7 col-xl-5">
<div id="toc" class="p-3 rounded my-4">
<ul class="">
<li class=""><a class="" href="https://rdmkit.rcos.nii.ac.jp/your-tasks/identifiers#%E3%83%87%E3%83%BC%E3%82%BF%E7%99%BB%E9%8C%B2%E6%99%82%E3%81%AB%E3%81%AF%E3%80%81%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AA%E8%AD%98%E5%88%A5%E5%AD%90%E3%82%92%E4%BD%BF%E3%81%88%E3%81%B0%E3%82%88%E3%81%84%E3%81%AE%E3%81%8B%EF%BC%9F">データ登録時には、どのような識別子を使えばよいのか？</a></li>
<li class=""><a class="" href="https://rdmkit.rcos.nii.ac.jp/your-tasks/identifiers#%E3%83%87%E3%83%BC%E3%82%BF%E5%85%AC%E9%96%8B%E3%81%AE%E9%9A%9B%E3%81%AB%E3%81%AF%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AA%E7%A8%AE%E9%A1%9E%E3%81%AE%E8%AD%98%E5%88%A5%E5%AD%90%E3%82%92%E4%BD%BF%E7%94%A8%E3%81%99%E3%81%B9%E3%81%8D%E3%81%8B%EF%BC%9F">データ公開の際にはどのような種類の識別子を使用すべきか？</a></li>
</ul>
</div>
</div>
<h2 id="データ登録時には、どのような識別子を使えばよいのか？" class="clickable-header top-level-header"><a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="https://rdmkit.rcos.nii.ac.jp/your-tasks/identifiers#%E3%83%87%E3%83%BC%E3%82%BF%E7%99%BB%E9%8C%B2%E6%99%82%E3%81%AB%E3%81%AF%E3%80%81%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AA%E8%AD%98%E5%88%A5%E5%AD%90%E3%82%92%E4%BD%BF%E3%81%88%E3%81%B0%E3%82%88%E3%81%84%E3%81%AE%E3%81%8B%EF%BC%9F"></a><strong>データ登録時には、どのような識別子を使えばよいのか？</strong></h2>
<h3><strong>概要</strong></h3>
<p>多くのデータやメタデータは、<a href="https://datacarpentry.org/spreadsheet-ecology-lesson/01-format-data.html" target="_blank" rel="noopener">表</a><span>（リンクは生態学の例）</span>の形で表現されます。これは、行ごとに記述された被験者やサンプル等の情報や観察される事象について、列ごとに入力された特性の定量的または定性的な測定値をセルの値として表現しています。これらの記録、変数、および値のそれぞれを一意の識別子で明確に特定できるようにしておくと、研究に大いに役立ちます。これは表形式ではないデータ（キーバリュー形式、非構造化データなど）にも当てはまります。データやメタデータには、形式によらず、常に識別子を用いるべきです。</p>
<p>研究機関やグループに、データやメタデータを記述し保存するための適切なシステムがある場合、このプロセスは研究者にとって非常に簡単なものになります。しかし、そのようなシステムがない場合、多くの研究者は、研究の記録を確認するために内部に「データベース」を構築しなければなりません。このような状況は多くの理由から非常に困難ですが、その解決策の<span>1</span>つに識別子の割り当てがあります。記録、変数、値に識別子を使用することで、自分や未来の自分、その他の人にとってデータの<a href="https://rdmkit.rcos.nii.ac.jp/about.html#fair%E5%8E%9F%E5%89%87%E3%81%AE%E9%87%8D%E8%A6%81%E6%80%A7">再利用性や相互運用性</a>が高まります。</p>
<p></p>
<h3><strong>考察</strong></h3>
<ul>
<li>研究プロジェクトを開始するにあたり、データ登録時にデータ入力のための適切なデータベースが研究所や研究グループにあるかどうかを確認します。通常、大規模かつ国際的な研究プロジェクトや、大企業、研究機関、病院には、データ入力用のユーザーインターフェースを備えたデータベース、電子データ収集（<span>EDC、 Electronic Data Capture</span>）システム、実験室情報管理システム（<span>LIMS、Laboratory Information Management System</span>）、電子実験ノート（<span>ELN、Electronic Lab Note</span>）などがあります。</li>
<li>データ入力システムの管理方法を選択できる場合は、<span>データセット内の各レコードや観測値に対する識別子の公開レベルを検討します</span>。<span>一意な識別子を用いてコンテキストを定義します。</span><span>個々のレコードごとにどのような識別子が適切であるかを定義することが重要です</span>。</li>
<ul>
<li>記録や観測された情報の識別子は、スプレッドシート内、研究プロジェクトファイル全体、あるいは研究所全体で一意であるべきでしょうか？識別子が参照するシステム（または「対象者」）は何でしょうか？</li>
<li>参照システムを変更する予定がありますか？ 参照システムを後から公開するのであれば、最初からグローバルに一意な識別子を割り当てることで、時間を節約できるかもしれません。</li>
<li>個々のレコードや観測値のための識別子は、データ登録中にインターネット上でオープンにアクセスできるようになるでしょうか？</li>
</ul>
<li>個々のレコードや観測値の識別子が、研究グループ内（イントラネット内）でのみ一意である必要があり、インターネット上では利用できない場合、それは「内部識別子または<a href="https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2001414#pbio-2001414-g001" target="_blank" rel="noopener">ローカル識別子</a>」とみなすことができます。ローカル識別子は、特定のローカルなコンテキスト（例えば、単一のコレクションやデータセット）でのみ区別ができるものです。</li>
<li>ローカル識別子は、表形式のデータセットの個々のレコードや観測値だけでなく、各変数や値（それぞれ、<a href="https://datacarpentry.org/spreadsheet-ecology-lesson/01-format-data.html" target="_blank" rel="noopener">表形式のデータセットの列やセル</a>）にも適用することができます。</li>
<li>データセット内の個々のレコード、変数、値の識別子は、オントロジー用語（<a href="https://rdmkit.rcos.nii.ac.jp/metadata_management#%E9%81%A9%E5%88%87%E3%81%AA%E8%AA%9E%E5%BD%99%E3%82%84%E3%82%AA%E3%83%B3%E3%83%88%E3%83%AD%E3%82%B8%E3%83%BC%E3%81%AF%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AB%E3%81%97%E3%81%A6%E8%A6%8B%E3%81%A4%E3%81%91%E3%82%8B%E3%81%AE%E3%81%8B%EF%BC%9F">メタデータ</a>のページを参照）や、JaLCなどの団体が提供するDOI、<span>DDBJ</span>などの公共データベースが提供するアクセッション番号を用いて割り当てることができます。ここでは、表形式のデータやメタデータを例に挙げましたが、データやメタデータの構造や形式によらず、同じ種類の識別子を適用することができます。</li>
</ul>
<h3><strong>ソリューション</strong></h3>
<ul>
<li>研究所や研究グループが集中型の電子データベース（<span>EDC</span>、<span>LIMS</span>、<span>ELN</span>など）を利用している場合は、データベース内の個々の記録や観測データに識別子を生成して割り当てるための関連ガイドラインに従います。研究機関によっては、識別子を集中的に管理しているところもあるので、担当チームに問い合わせましょう。</li>
<li>内部またはローカルの識別子は、特定の命名規則や<a href="https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2001414#pbio-2001414-g001" target="_blank" rel="noopener">正規表現</a>などの形式的なパターンに基づいた固有の名前でなければなりません。表現形式をスプレッドシートやソフトウェアに合うように設定します。表現形式については、必ずドキュメント（<span>README</span>ファイルまたはコードブック）に記載します。曖昧な表現は避けます。</li>
<li>ローカル識別子に意味を埋め込むことは避けます。短い名前で意味を伝える必要がある場合は、人間が読みやすいように「ラベル」を実装します。</li>
<li>問題のある文字やパターンをローカル識別子に使用してはなりません。問題のある文字列（例えばプログラム内で「全件」を意味する場合があるアスタリスク記号＊など）は、ソフトウェアによっては誤って解釈されることがあります。このような場合には、管理者がバグを修正するか、このような可能性のある問題を文書で明示的に宣言する方が良いでしょう。</li>
<li>DDBJなどの公共データベースで使用されているオントロジー用語やアクセッション番号を適用して、遺伝子、タンパク質、化合物、病気、種などを一意に特定することができます。自分自身との相互運用性を最も高めるために、各タイプについて正確に<span>1</span>つを選択します。</li>
<li>オントロジーが整備されている分野では、オントロジーを変数に適用することで、変数間の明確な構造と関係を保つことができます（例：「化合物と用量」、「変数と単位」）。オントロジー用語をスプレッドシートに統合できるソフトウェアには、<a href="https://rightfield.org.uk/" target="_blank" rel="noopener"><span>RightField</span></a>と<a href="https://github.com/ISA-tools/OntoMaton#readme" target="_blank" rel="noopener"><span>OntoMaton</span></a>があります。</li>
<li>毎日新しい行が追加される表形式で各レコードを記録している場合は、バージョン管理システムを使用して変更を追跡します。多くのクラウド<a href="https://rdmkit.rcos.nii.ac.jp/storage#%E3%83%87%E3%83%BC%E3%82%BF%E5%8F%8E%E9%9B%86%E6%99%82%E3%81%AE%E3%82%B9%E3%83%88%E3%83%AC%E3%83%BC%E3%82%B8%E3%81%AB%E5%BF%85%E8%A6%81%E3%81%AA%E6%A9%9F%E8%83%BD%E3%81%A8%E3%81%AF%EF%BC%9F">ストレージ</a>サービスでは、自動バージョニング機能を提供しているほか、バージョニングログを記録しています（<a href="https://rdmkit.rcos.nii.ac.jp/data_organisation">データ整理</a>のページを参照）。表形式のデータやメタデータファイルは、突然重要な列が削除されたり、複製されないようにする必要があります。説明のために表データやメタデータファイルに関する文書（<span>README</span>ファイル、コードブックなど）も必要です。</li>
<li>頻繁に更新されるデータベースからデータを収集する場合、データベース<span>ID</span>だけでなく、使用したバージョン（ファイル更新日時、またはデータ収集の日時を記録）や実行した正確なクエリを記録しておくことをお勧めします。こうすることで、タイムスタンプ付きのデータストアに対して正確なクエリを再実行することができます（<a href="https://zenodo.org/record/1406002#.Ye44ufvP2Um" target="_blank" rel="noopener">進化するデータのデータ引用</a>）。</li>
</ul>
<p>既存のデータセットを再利用する場合は、出所を示すために提供された識別子を保持し、システムに応じて新しい識別子を付与しますが、元の識別子との関係を保持して出所を追跡できるようにします。スプレッドシートを使用するか、マッピングファイルを作成して、実績と内部識別子の関係を維持しましょう。</p>
<ul>
<li>大規模な研究プロジェクトや研究機関のために、集中型の機械可読データベース、<span>EDC</span>、<span>LIMS</span>、<span>ELN</span>（イントラネット上で利用可能）を構築するには、データベース、プログラミング、コンピュータサイエンスなどの高度な専門技術が必要になる場合があります。このようなシステムを導入するためのソフトウェアやツールについては、<span>IT</span>チームやその分野の専門家に相談してみることをお勧めします。</li>
</ul>
<h2 id="データ公開の際にはどのような種類の識別子を使用すべきか？" class="clickable-header top-level-header"><a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="https://rdmkit.rcos.nii.ac.jp/your-tasks/identifiers#%E3%83%87%E3%83%BC%E3%82%BF%E5%85%AC%E9%96%8B%E3%81%AE%E9%9A%9B%E3%81%AB%E3%81%AF%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AA%E7%A8%AE%E9%A1%9E%E3%81%AE%E8%AD%98%E5%88%A5%E5%AD%90%E3%82%92%E4%BD%BF%E7%94%A8%E3%81%99%E3%81%B9%E3%81%8D%E3%81%8B%EF%BC%9F"></a><strong>データ公開の際にはどのような種類の識別子を使用すべきか？</strong></h2>
<h3><strong>概要</strong></h3>
<p>すべての記録と測定が収集され、データセット全体を他の人と共有する準備ができたら、データセットをより FAIR にするために、グローバルに一意な永続的識別子を割り当てるのが良い方法です。「<span>GUID</span>（<span>Globally Unique Identifier</span>）とは、あらゆるものの識別子として使用できる固有の情報であり、<span>GUID</span>の一意性は、それを生成するために使用されたアルゴリズムに依存します」（<a href="http://guid.one/guid" target="_blank" rel="noopener">What is a GUID</a>）。「永続的識別子<span>(PID)</span>とは、ある資源へ長期的に参照をするための識別子です。そのリソースとは、出版物、データセット、もしくは人かもしれません。同様に、それは科学的サンプル、資金提供団体、地理的座標、未発表のレポート、ソフトウェアの一部かもしれません。それが何であれ、<span>PID</span>の主な目的は、確実に識別し、検証し、位置を特定するために必要な情報を提供することです。<span>PID</span>は、アイテム自体ではなく、アイテムを記述する一連のメタデータに接続されることがあります」（<a href="https://www.openaire.eu/what-is-a-persistent-identifier" target="_blank" rel="noopener"><span>What is a persistent identifier, OpenAIRE</span></a>）。つまり、<span>PID</span>を持つデータセットは、そのデータセットの場所やウェブアドレス（<span>URL</span>）が変わっても、見つけることができるということです。<span>PID</span>を管理する中央レジストリは、与えられた<span>PID</span>がデジタルリソースの現在の位置を示すことを保証します。<a href="https://en.wikipedia.org/wiki/Persistent_identifier" target="_blank" rel="noopener"><span>PID</span></a>には、<a href="https://www.doi.org/" target="_blank" rel="noopener"><span>DOI</span></a>、<a href="https://sites.google.com/site/persistenturls/" target="_blank" rel="noopener"><span>PURL</span></a>、<a href="http://www.handle.net/" target="_blank" rel="noopener">Handle</a>、<a href="https://www.igsn.org/" target="_blank" rel="noopener">IGSN</a>、<a href="https://en.wikipedia.org/wiki/Uniform_Resource_Name" target="_blank" rel="noopener"><span>URN</span></a>などの種類があります。<span>(</span><a href="https://www.nii.ac.jp/irp/archive/translation/PersistentIdentifiers/tonkin/tonkin.htm" target="_blank" rel="noopener">永続識別子<span>: </span>その選択肢の考察</a>）</p>
<p><strong></strong></p>
<h3><strong>考察</strong></h3>
<p>PIDは、あなたのデジタルオブジェクト（データセットやリソース）を引用可能な状態にし、あなたの研究成果を業績と主張して認められるために不可欠です。また、他の人の研究成果を再利用する際には、それを引用しなければなりません。</p>
<p>グローバルに一意な永続的識別子を取得するにはいくつかの方法がありますが、あなたのデータセットやリソースにとってどの方法が最適なのかを決める必要があります。</p>
<ul>
<li>既存の公開リポジトリへの公開
<ul>
<li>ほとんどの種類のデータでは、リポジトリがグローバルに一意の永続的な識別子またはアクセッション番号を割り当てるため、通常はこの方法が最適です。内部のデータベースを更新して、公開されている識別子との関係を維持します。</li>
</ul>
</li>
<li>ローカルデータベースの一般公開
<ul>
<li>このためには、リソースが持続可能な計画を持っていること、バージョン管理や識別子の命名に関するポリシーを持っていることが必要です。この方法は、データを適切なレベルで公開できる公的なリポジトリがない場合には有効な解決策となりますが、将来的なメンテナンスや可用性に関しては、多くの責任を負うことになります。</li>
</ul>
</li>
</ul>
<p><strong>ソリューション</strong></p>
<ul>
<li>既存の公開リポジトリにデータを公開したい場合は、まず<span> 永続的な <a href="https://rdmkit.rcos.nii.ac.jp/data_publication">データ公開</a></span>のページをご覧ください。リポジトリはあなたのデータにグローバルに一意な永続的識別子を提供します。公開後にデータセットを編集・更新する必要がある場合は、そのリポジトリのガイドラインを確認します。一般的なリポジトリでは、公開されたデータセットや文書の更新にバージョニング<span>DOI</span>を使用します。（<a href="https://doi.org/10.11502/rd_guideline_ja" target="_blank" rel="noopener">研究データへの<span>DOI</span>登録ガイドライン</a>をご覧ください ）</li>
<li>機関のパブリックリポジトリでデータを公開したい場合は、その機関に<a href="http://identifiers.org/" target="_blank" rel="noopener"><span>identifiers.org</span></a>で名前空間を取得してもらい、データのグローバルに一意な永続的識別子を取得します。</li>
<li>ご自身のデータベースを公開するためのリソースやスキルをお持ちの方は、<a href="http://identifiers.org/" target="_blank" rel="noopener"><span>identifiers.org</span></a>で名前空間を取得し、データのグローバルに一意な識別子を取得します。</li>
</ul>