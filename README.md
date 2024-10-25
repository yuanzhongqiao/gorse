<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="36647208" _msthash="281">Gorse Recommender 系统引擎</h1><a id="user-content-gorse-recommender-system-engine" class="anchor" aria-label="永久链接： Gorse Recommender System Engine" href="#gorse-recommender-system-engine" _mstaria-label="1296880" _msthash="282"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/https://github.comgorse-io/gorse/blob/master/assets/gorse.png"><img width="160" src="https://github.com/gorse-io/gorse/raw/master/assets/gorse.png" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/06f4bdb54bb6f07d2f62e1d29486d9c2cce5a16037da93ea1b19dd582aa883af/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f676f2d6d6f642f676f2d76657273696f6e2f7a68656e6768616f7a2f676f727365"><img src="https://camo.githubusercontent.com/06f4bdb54bb6f07d2f62e1d29486d9c2cce5a16037da93ea1b19dd582aa883af/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f676f2d6d6f642f676f2d76657273696f6e2f7a68656e6768616f7a2f676f727365" alt="" data-canonical-src="https://img.shields.io/github/go-mod/go-version/zhenghaoz/gorse" style="max-width: 100%;"></a>
<a href="https://github.com/zhenghaoz/gorse/actions?query=workflow%3Abuild"><img src="https://github.com/zhenghaoz/gorse/workflows/build/badge.svg" alt="建" style="max-width: 100%;" _mstalt="61711" _msthash="283"></a>
<a href="https://codecov.io/gh/gorse-io/gorse" rel="nofollow"><img src="https://camo.githubusercontent.com/fe4150e56cf69f3208d9d412ca720e6cdb95e2e308f1310b59e6cce9dc9c7e10/68747470733a2f2f636f6465636f762e696f2f67682f676f7273652d696f2f676f7273652f6272616e63682f6d61737465722f67726170682f62616467652e737667" alt="Codecov 公司" data-canonical-src="https://codecov.io/gh/gorse-io/gorse/branch/master/graph/badge.svg" style="max-width: 100%;" _mstalt="96798" _msthash="284"></a>
<a href="https://goreportcard.com/report/github.com/zhenghaoz/gorse" rel="nofollow"><img src="https://camo.githubusercontent.com/8843bb6aa506c4881b7ea9478c327ccbbc74c5471fc92f6ead3aba71877c2eaf/68747470733a2f2f676f7265706f7274636172642e636f6d2f62616467652f6769746875622e636f6d2f7a68656e6768616f7a2f676f727365" alt="Go 成绩单" data-canonical-src="https://goreportcard.com/badge/github.com/zhenghaoz/gorse" style="max-width: 100%;" _mstalt="196274" _msthash="285"></a>
<a href="https://godoc.org/github.com/zhenghaoz/gorse" rel="nofollow"><img src="https://camo.githubusercontent.com/09d49780c9e44f7110f98b4c17abc7ec77eed45899c37eef51373b0897e463ed/68747470733a2f2f676f646f632e6f72672f6769746875622e636f6d2f7a68656e6768616f7a2f676f7273653f7374617475732e737667" alt="GoDoc 文档" data-canonical-src="https://godoc.org/github.com/zhenghaoz/gorse?status.svg" style="max-width: 100%;" _mstalt="54548" _msthash="286"></a>
<a href="https://discord.gg/x6gAtNNkAE" rel="nofollow"><img src="https://camo.githubusercontent.com/d80339690724db2d4f3b3d6ba9079c4e86fc67a1ab55a13c8207c06d1d9408cf/68747470733a2f2f696d672e736869656c64732e696f2f646973636f72642f383330363335393334323130353838373433" alt="不和" data-canonical-src="https://img.shields.io/discord/830635934210588743" style="max-width: 100%;" _mstalt="93990" _msthash="287"></a>
<a href="https://twitter.com/gorse_io" rel="nofollow"><img src="https://camo.githubusercontent.com/fc591febb00adec270755f218e35dc2925e2193f4c9a1ce8de9a4a82b6e50fd2/68747470733a2f2f696d672e736869656c64732e696f2f747769747465722f666f6c6c6f772f676f7273655f696f3f6c6162656c3d466f6c6c6f77267374796c653d736f6369616c" alt="Twitter 关注" data-canonical-src="https://img.shields.io/twitter/follow/gorse_io?label=Follow&amp;style=social" style="max-width: 100%;" _mstalt="235079" _msthash="288"></a></p>
<p dir="auto" _msttexthash="1992663504" _msthash="289">Gorse 是一个用 Go 编写的开源推荐系统。Gorse 的目标是成为一个通用的开源推荐系统，可以快速引入到各种在线服务中。通过将项目、用户和交互数据导入 Gorse，系统将自动训练模型为每个用户生成推荐。项目特点如下。</p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/gorse-io/gorse/blob/master/assets/workflow.png"><img width="520" src="https://github.com/gorse-io/gorse/raw/master/assets/workflow.png" style="max-width: 100%;"></a></p>
<ul dir="auto">
<li _msttexthash="250134807" _msthash="290"><strong _istranslated="1">多源：</strong>从 Popular， latest， user-based， based-item 和 collaborative filtering 中推荐项目。</li>
<li _msttexthash="97149130" _msthash="291"><strong _istranslated="1">自动 ML：</strong>在后台自动搜索最佳推荐模型。</li>
<li _msttexthash="200952336" _msthash="292"><strong _istranslated="1">分布式预测：</strong>支持在单节点训练后的推荐阶段进行水平扩展。</li>
<li _msttexthash="108712253" _msthash="293"><strong _istranslated="1">RESTful API：</strong>为数据 CRUD 和建议请求公开 RESTful API。</li>
<li _msttexthash="147697251" _msthash="294"><strong _istranslated="1">在线评估：</strong>根据最近插入的反馈分析在线推荐效果。</li>
<li _msttexthash="181205687" _msthash="295"><strong _istranslated="1">挡泥板：</strong>提供用于数据管理、系统监控和集群状态检查的 GUI。</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="11905335" _msthash="296">快速开始</h2><a id="user-content-quick-start" class="anchor" aria-label="永久链接：快速入门" href="#quick-start" _mstaria-label="437814" _msthash="297"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="302293524" _msthash="298">游乐场模式是为初学者准备的。只需通过以下命令为 GitHub 存储库设置推荐系统即可。</p>
<ul dir="auto">
<li _msttexthash="23390705" _msthash="299">Linux/macOS的：</li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>curl -fsSL https://gorse.io/playground <span class="pl-k">|</span> bash</pre><div class="zeroclipboard-container">
   
  </div></div>
<ul dir="auto">
<li _msttexthash="19941662" _msthash="300">码头工人：</li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker run -p 8088:8088 zhenghaoz/gorse-in-one --playground</pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="213844501" _msthash="301">playground 模式将从 <a href="https://gitrec.gorse.io/" rel="nofollow" _mstmutation="1" _istranslated="1">GitRec</a> 下载数据并将其导入 Gorse。控制面板位于 。</font><code>http://localhost:8088</code></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/gorse-io/gorse/blob/master/assets/dashboard.jpeg"><img width="720" src="/gorse-io/gorse/raw/master/assets/dashboard.jpeg" style="max-width: 100%;"></a></p>
<p dir="auto" _msttexthash="1483505907" _msthash="302">在 “Tasks” 页面上完成 “Find neighbors of items” 任务后，尝试在 Gorse 中插入多个反馈。假设 Bob 是一名前端开发人员，他在 GitHub 中为多个前端存储库加了星标。我们将他的星级反馈插入到 Gorse 中。</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">read</span> -d <span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span> JSON <span class="pl-s"><span class="pl-k">&lt;&lt;</span> <span class="pl-k">EOF</span></span>
<span class="pl-s">[</span>
<span class="pl-s">    { \"FeedbackType\": \"star\", \"UserId\": \"bob\", \"ItemId\": \"vuejs:vue\", \"Timestamp\": \"2022-02-24\" },</span>
<span class="pl-s">    { \"FeedbackType\": \"star\", \"UserId\": \"bob\", \"ItemId\": \"d3:d3\", \"Timestamp\": \"2022-02-25\" },</span>
<span class="pl-s">    { \"FeedbackType\": \"star\", \"UserId\": \"bob\", \"ItemId\": \"dogfalo:materialize\", \"Timestamp\": \"2022-02-26\" },</span>
<span class="pl-s">    { \"FeedbackType\": \"star\", \"UserId\": \"bob\", \"ItemId\": \"mozilla:pdf.js\", \"Timestamp\": \"2022-02-27\" },</span>
<span class="pl-s">    { \"FeedbackType\": \"star\", \"UserId\": \"bob\", \"ItemId\": \"moment:moment\", \"Timestamp\": \"2022-02-28\" }</span>
<span class="pl-s">]</span>
<span class="pl-s"><span class="pl-k">EOF</span></span>

curl -X POST http://127.0.0.1:8088/api/feedback \
   -H <span class="pl-s"><span class="pl-pds">'</span>Content-Type: application/json<span class="pl-pds">'</span></span> \
   -d <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$JSON</span><span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto" _msttexthash="272579541" _msthash="303">然后，从 Gorse 获取 10 件推荐物品。我们可以发现 Bob 推荐使用与 frontend 相关的仓库。</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>curl http://127.0.0.1:8088/api/recommend/bob<span class="pl-k">?</span>n=10</pre><div class="zeroclipboard-container">
   
  </div></div>
<details>
<summary _msttexthash="21144175" _msthash="304">输出示例：</summary>
<div class="highlight highlight-source-json notranslate position-relative overflow-auto" dir="auto"><pre>[
 <span class="pl-s"><span class="pl-pds">"</span>mbostock:d3<span class="pl-pds">"</span></span>,
 <span class="pl-s"><span class="pl-pds">"</span>nt1m:material-framework<span class="pl-pds">"</span></span>,
 <span class="pl-s"><span class="pl-pds">"</span>mdbootstrap:vue-bootstrap-with-material-design<span class="pl-pds">"</span></span>,
 <span class="pl-s"><span class="pl-pds">"</span>justice47:f2-vue<span class="pl-pds">"</span></span>,
 <span class="pl-s"><span class="pl-pds">"</span>10clouds:cyclejs-cookie<span class="pl-pds">"</span></span>,
 <span class="pl-s"><span class="pl-pds">"</span>academicpages:academicpages.github.io<span class="pl-pds">"</span></span>,
 <span class="pl-s"><span class="pl-pds">"</span>accenture:alexia<span class="pl-pds">"</span></span>,
 <span class="pl-s"><span class="pl-pds">"</span>addyosmani:tmi<span class="pl-pds">"</span></span>,
 <span class="pl-s"><span class="pl-pds">"</span>1wheel:d3-starterkit<span class="pl-pds">"</span></span>,
 <span class="pl-s"><span class="pl-pds">"</span>acdlite:redux-promise<span class="pl-pds">"</span></span>
]</pre><div class="zeroclipboard-container">
   
  </div></div>
</details>
<blockquote>
<p dir="auto" _msttexthash="219750570" _msthash="305">确切的输出可能与示例不同，因为 Playground 数据集会随时间而变化。</p>
</blockquote>
<p dir="auto" _msttexthash="64340939" _msthash="306">有关更多信息，请访问：</p>
<ul dir="auto">
<li _msttexthash="20220538" _msthash="307">阅读<a href="https://gorse.io/docs/master" rel="nofollow" _istranslated="1">官方文件</a></li>
<li _msttexthash="22283651" _msthash="308">访问<a href="https://gitrec.gorse.io/" rel="nofollow" _istranslated="1">官方演示</a></li>
<li _msttexthash="34733959" _msthash="309">在 <a href="https://discord.gg/x6gAtNNkAE" rel="nofollow" _istranslated="1">Discord</a> 或 <a href="https://github.com/gorse-io/gorse/discussions" _istranslated="1">GitHub 上讨论</a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5495750" _msthash="310">建筑</h2><a id="user-content-architecture" class="anchor" aria-label="永久链接： 架构" href="#architecture" _mstaria-label="516191" _msthash="311"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="582621208" _msthash="312">Gorse 是一个单节点训练和分布式预测推荐系统。Gorse 将数据存储在 MySQL、MongoDB 或 Postgres 中，中间结果缓存在 Redis、MySQL、MongoDB 和 Postgres 中。</p>
<ol dir="auto">
<li _msttexthash="128507873" _msthash="313">集群由一个主节点、多个 Worker 节点和 Server 节点组成。</li>
<li _msttexthash="209700699" _msthash="314">主节点负责模型训练、非个性化物品推荐、配置管理和成员管理。</li>
<li _msttexthash="111684209" _msthash="315">服务器节点负责公开 RESTful API 和在线实时推荐。</li>
<li _msttexthash="114590710" _msthash="316">Worker 节点负责为每个用户提供离线推荐。</li>
</ol>
<p dir="auto" _msttexthash="390381082" _msthash="317">此外，管理员还可以通过主节点上的仪表板执行系统监控、数据导入和导出以及系统状态检查。</p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/gorse-io/gorse/blob/master/assets/architecture.png"><img width="520" src="https://github.com/gorse-io/gorse/raw/master/assets/architecture.png" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="6354283" _msthash="318">贡献</h2><a id="user-content-contributors" class="anchor" aria-label="永久链接： 贡献者" href="#contributors" _mstaria-label="528866" _msthash="319"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<a href="https://github.com/zhenghaoz/gorse/graphs/contributors">
  <img src="https://camo.githubusercontent.com/913dae00d8bde4cace268fd5b9b464ea22d46d5fb64d061f53e4939798654e62/68747470733a2f2f636f6e747269622e726f636b732f696d6167653f7265706f3d7a68656e6768616f7a2f676f727365" data-canonical-src="https://contrib.rocks/image?repo=zhenghaoz/gorse" style="max-width: 100%;">
</a>
<p dir="auto" _msttexthash="371474220" _msthash="320">任何贡献都值得赞赏：报告错误、提供建议或创建拉取请求。有关详细信息<a href="/gorse-io/gorse/blob/master/CONTRIBUTING.md" _istranslated="1">，请阅读 CONTRIBUTING.md</a>。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="6523322" _msthash="321">确认</h2><a id="user-content-acknowledgments" class="anchor" aria-label="永久链接：致谢" href="#acknowledgments" _mstaria-label="642798" _msthash="322"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><code>gorse</code><font _mstmutation="1" _msttexthash="50012638" _msthash="323">的灵感来自以下项目：</font></p>
<ul dir="auto">
<li><a href="https://github.com/guoguibing/librec" _msttexthash="12645373" _msthash="324">郭桂兵的 librec</a></li>
<li><a href="https://github.com/NicolasHug/Surprise" _msttexthash="18067829" _msthash="325">Nicolas Hug 的惊喜</a></li>
<li><a href="https://github.com/golang-samples/gopher-vector" _msttexthash="29453645" _msthash="326">Golang Samples 的 gopher 向量</a></li>
</ul>
</article></div>
