<h2 align="center">
  CLRA中文词汇特征分析器 V1.0 使用手册
</h2>

<p
  class="MsoNormal"
  align="center"
  style="
    margin-bottom: 7.8pt;
    mso-para-margin-bottom: 0.5gd;
    text-align: center;
    line-height: 150%;
  "
>
  <span
    lang="EN-US"
    style="
      font-size: 12pt;
      line-height: 150%;
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 楷体;
    "
    >2023/08/30<o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  style="text-indent: 21.4pt; mso-char-indent-count: 2; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >CLRA</span
    ></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: 宋体;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
      "
      >工具</span
    ></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
    >
      (Chinese Lexical Richness Analyzer)</span
    ></b
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
  </span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >由北京师范大学国际中文教育学院胡韧奋课题组主持研发，旨在为国际中文教育领域内的教材编撰、考试命题、学生写作以及口语产出研究提供<b
      style="mso-bidi-font-weight: normal"
      >词汇维度</b
    >的量化分析支持。</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #1f2328;
      background: white;
    "
    >CLRA</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >参考《国际中文教育中文水平等级标准》三等九级词表，支持文本标注（分词、词性、词语等级）、词表生成、词汇复杂度和词汇多样性等多维度指标分析等功能。</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="
    margin-top: 7.8pt;
    margin-right: 0cm;
    margin-bottom: 0cm;
    margin-left: 17.85pt;
    margin-bottom: 0.0001pt;
    mso-para-margin-top: 0.5gd;
    mso-para-margin-right: 0cm;
    mso-para-margin-bottom: 0cm;
    mso-para-margin-left: 17.85pt;
    mso-para-margin-bottom: 0.0001pt;
    text-indent: -17.85pt;
    mso-char-indent-count: 0;
    line-height: 150%;
    mso-list: l4 level1 lfo8;
  "
>
  <![if !supportLists]><b
    ><span
      lang="EN-US"
      style="
        font-size: 14pt;
        line-height: 150%;
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 'Times New Roman';
      "
      ><span style="mso-list: Ignore"
        >1.<span style="font: 7pt 'Times New Roman'"
          >&nbsp;&nbsp;&nbsp;
        </span></span
      ></span
    ></b
  ><![endif]><b
    ><span
      style="
        font-size: 14pt;
        line-height: 150%;
        font-family: '微软雅黑', sans-serif;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
      "
      >下载分析器</span
    ></b
  ><b
    ><span
      lang="EN-US"
      style="
        font-size: 14pt;
        line-height: 150%;
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 微软雅黑;
      "
      ><o:p></o:p></span
  ></b>
</p>

<p
  class="MsoNormal"
  style="text-indent: 21pt; mso-char-indent-count: 2; line-height: 150%"
>
  <span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #1f2328;
      background: white;
    "
    >CLRA</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #1f2328;
      background: white;
    "
    >工具提供了</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #1f2328;
      background: white;
    "
    >Windows, MacOS (Intel), MacOS (Apple M1)</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #1f2328;
      background: white;
    "
    >三种客户端程序，</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >填写试用申请后可获得下载链接：</span
  ><span class="MsoHyperlink"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      ><a href="https://www.wjx.cn/vm/rUtXWDS.aspx" target="_blank"
        >https://www.wjx.cn/vm/rUtXWDS.aspx#</a
      ></span
    ></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >。请<span style="color: #1f2328; background: white"
      >下载系统对应的程序，解压缩后无需安装：</span
    ></span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="
    margin-left: 42pt;
    text-indent: -21pt;
    mso-char-indent-count: 0;
    line-height: 150%;
    mso-list: l5 level1 lfo10;
  "
>
  <![if !supportLists]><span
    lang="EN-US"
    style="
      font-family: Wingdings;
      mso-fareast-font-family: Wingdings;
      mso-bidi-font-family: Wingdings;
      color: #1f2328;
    "
    ><span style="mso-list: Ignore"
      >➢<span style="font: 7pt 'Times New Roman'">&nbsp; </span></span
    ></span
  ><![endif]><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #1f2328;
      background: white;
    "
    >Windows</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #1f2328;
      background: white;
    "
    >系统：双击直接打开；</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #1f2328;
      background: white;
    "
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="
    margin-top: 0cm;
    margin-right: 0cm;
    margin-bottom: 7.8pt;
    margin-left: 42pt;
    mso-para-margin-top: 0cm;
    mso-para-margin-right: 0cm;
    mso-para-margin-bottom: 0.5gd;
    mso-para-margin-left: 42pt;
    text-indent: -21pt;
    mso-char-indent-count: 0;
    line-height: 150%;
    mso-list: l5 level1 lfo10;
  "
>
  <![if !supportLists]><span
    lang="EN-US"
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: Wingdings;
      mso-fareast-font-family: Wingdings;
      mso-bidi-font-family: Wingdings;
    "
    ><span style="mso-list: Ignore"
      >➢<span style="font: 7pt 'Times New Roman'">&nbsp; </span></span
    ></span
  ><![endif]><span
    lang="EN-US"
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #1f2328;
    "
    >Mac OS</span
  ><span
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #1f2328;
    "
    >系统：<span style="background: white"
      >首次运行程序如提示开发者身份未验证，请</span
    ></span
  ><code
    ><b style="mso-bidi-font-weight: normal"
      ><span
        style="
          mso-ansi-font-size: 10.5pt;
          mso-bidi-font-size: 10.5pt;
          line-height: 150%;
          mso-ascii-font-family: 'Times New Roman';
          mso-hansi-font-family: 'Times New Roman';
          mso-bidi-font-family: 'Times New Roman';
          color: red;
        "
        >右键点击</span
      ></b
    ></code
  ><span
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #1f2328;
      background: white;
    "
    >打开，为方便后续使用，还可将程序拖至</span
  ><span
    lang="EN-US"
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #1f2328;
      background: white;
    "
    >Mac</span
  ><span
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #1f2328;
      background: white;
    "
    >应用程序目录，之后可通过</span
  ><code
    ><span
      style="
        mso-ansi-font-size: 10.5pt;
        mso-bidi-font-size: 10.5pt;
        line-height: 150%;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
        color: #1f2328;
      "
      >启动台</span
    ></code
  ><span
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #1f2328;
      background: white;
    "
    >快捷访问</span
  ><span
    lang="EN-US"
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #1f2328;
      background: white;
    "
    >CLRA</span
  ><span
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #1f2328;
      background: white;
    "
    >。</span
  ><span
    lang="EN-US"
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
    "
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  align="center"
  style="text-align: center; line-height: 150%"
>
  <span
    lang="EN-US"
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      mso-no-proof: yes;
    "
    ><!--[if gte vml 1
      ]><v:shapetype
        id="_x0000_t75"
        coordsize="21600,21600"
        o:spt="75"
        o:preferrelative="t"
        path="m@4@5l@4@11@9@11@9@5xe"
        filled="f"
        stroked="f"
      >
        <v:stroke joinstyle="miter" />
        <v:formulas>
          <v:f eqn="if lineDrawn pixelLineWidth 0" />
          <v:f eqn="sum @0 1 0" />
          <v:f eqn="sum 0 0 @1" />
          <v:f eqn="prod @2 1 2" />
          <v:f eqn="prod @3 21600 pixelWidth" />
          <v:f eqn="prod @3 21600 pixelHeight" />
          <v:f eqn="sum @0 0 1" />
          <v:f eqn="prod @6 1 2" />
          <v:f eqn="prod @7 21600 pixelWidth" />
          <v:f eqn="sum @8 21600 0" />
          <v:f eqn="prod @7 21600 pixelHeight" />
          <v:f eqn="sum @10 21600 0" />
        </v:formulas>
        <v:path o:extrusionok="f" gradientshapeok="t" o:connecttype="rect" />
        <o:lock v:ext="edit" aspectratio="t" /> </v:shapetype
      ><v:shape
        id="图片_x0020_3"
        o:spid="_x0000_i1026"
        type="#_x0000_t75"
        style="
          width: 267pt;
          height: 292pt;
          visibility: visible;
          mso-wrap-style: square;
        "
      >
        <v:imagedata
          src="images/image001.png"
          o:title=""
        /> </v:shape><!
    [endif]--><![if !vml]><img
      border="0"
      width="267"
      height="292"
      src="images/image001.png"
      v:shapes="图片_x0020_3"
    /><![endif]></span
  ><span
    lang="EN-US"
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
    "
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  align="center"
  style="
    margin-bottom: 7.8pt;
    mso-para-margin-bottom: 0.5gd;
    text-align: center;
    line-height: 150%;
  "
>
  <span
    lang="EN-US"
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
    "
    >CLRA</span
  ><span
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >界面</span
  ><span
    lang="EN-US"
    style="
      mso-bidi-font-size: 10.5pt;
      line-height: 150%;
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
    "
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="
    margin-left: 18pt;
    text-indent: -18pt;
    mso-char-indent-count: 0;
    line-height: 150%;
    mso-list: l4 level1 lfo8;
  "
>
  <![if !supportLists]><b
    ><span
      lang="EN-US"
      style="
        font-size: 14pt;
        line-height: 150%;
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 'Times New Roman';
      "
      ><span style="mso-list: Ignore"
        >2.<span style="font: 7pt 'Times New Roman'"
          >&nbsp;&nbsp;&nbsp;
        </span></span
      ></span
    ></b
  ><![endif]><b
    ><span
      style="
        font-size: 14pt;
        line-height: 150%;
        font-family: '微软雅黑', sans-serif;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
      "
      >文本标注工具</span
    ></b
  ><b
    ><span
      lang="EN-US"
      style="
        font-size: 14pt;
        line-height: 150%;
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 微软雅黑;
      "
      ><o:p></o:p></span
  ></b>
</p>

<p
  class="MsoNormal"
  style="text-indent: 21pt; mso-char-indent-count: 2; line-height: 150%"
>
  <span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >文本标注工具单次可处理</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >10</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >万字以内文本，包含<b style="mso-bidi-font-weight: normal">分词</b>、<b
      style="mso-bidi-font-weight: normal"
      >标注词性</b
    >、<b style="mso-bidi-font-weight: normal">标注新标准词语等级</b>、<b
      style="mso-bidi-font-weight: normal"
      >标注新标准词语等级（含扩充词表）</b
    >四项功能。</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  style="margin-top: 7.8pt; mso-para-margin-top: 0.5gd; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: '微软雅黑', sans-serif;
        mso-bidi-font-family: 'Times New Roman';
      "
      >2.1
    </span></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: '微软雅黑', sans-serif;
        mso-bidi-font-family: 'Times New Roman';
      "
      >文本标注工具使用方法<span lang="EN-US"><o:p></o:p></span></span
  ></b>
</p>

<p
  class="MsoNormal"
  style="text-indent: 21.4pt; mso-char-indent-count: 2; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >Step1:</span
    ></b
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
  </span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >将待分析文本粘贴至文本框内，文本框输入支持最长</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: red;
    "
    >10</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: red;
    "
    >万字符</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >；</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  style="text-indent: 21.4pt; mso-char-indent-count: 2; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >Step2:</span
    ></b
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
  </span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >选择用户所需要的对应功能，点击</span
  ><span
    lang="EN-US"
    style="font-family: 宋体; mso-bidi-font-family: 'Times New Roman'"
    >“</span
  ><span style="font-family: 宋体; mso-bidi-font-family: 'Times New Roman'"
    >文本标注<span lang="EN-US">”</span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >（<span style="color: red">注：</span></span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: red;
    "
    >“</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: red;
    "
    >新标准等级</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: red;
    "
    >”</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: red;
    "
    >和</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: red;
    "
    >“</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: red;
    "
    >新标准等级（含扩充词表）</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: red;
    "
    >”</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: red;
    "
    >不可同时选择</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >）；</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  style="text-indent: 21.4pt; mso-char-indent-count: 2; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >Step3:</span
    ></b
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
  </span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >文本框内显示标注成功后的文本，如需输入新文本，点击</span
  ><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="font-family: 宋体; mso-bidi-font-family: 'Times New Roman'"
      >“</span
    ></b
  ><b style="mso-bidi-font-weight: normal"
    ><span style="font-family: 宋体; mso-bidi-font-family: 'Times New Roman'"
      >清空文本<span lang="EN-US">”</span></span
    ></b
  ><span style="font-family: 宋体; mso-bidi-font-family: 'Times New Roman'"
    >即</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >可。</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  style="margin-top: 7.8pt; mso-para-margin-top: 0.5gd; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: '微软雅黑', sans-serif;
        mso-bidi-font-family: 'Times New Roman';
      "
      >2.2</span
    ></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: '微软雅黑', sans-serif;
        mso-bidi-font-family: 'Times New Roman';
      "
      >文本标注结果说明<span lang="EN-US"><o:p></o:p></span></span
  ></b>
</p>

<p
  class="MsoListParagraph"
  style="margin-left: 0cm; line-height: 150%; mso-list: l2 level1 lfo4"
>
  <![if !supportLists]><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 'Times New Roman';
      "
      ><span style="mso-list: Ignore"
        >A.<span style="font: 7pt 'Times New Roman'"
          >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </span></span
      ></span
    ></b
  ><![endif]><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >在具体的标注结果中，各等级词语的标注结果对应等级数字，七至九级对应数字</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >7</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >；</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="margin-left: 0cm; line-height: 150%; mso-list: l2 level1 lfo4"
>
  <![if !supportLists]><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 'Times New Roman';
      "
      ><span style="mso-list: Ignore"
        >B.<span style="font: 7pt 'Times New Roman'"
          >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </span></span
      ></span
    ></b
  ><![endif]><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >超纲词标为</span
  ><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >“<span class="SpellE">oov</span>”</span
    ></b
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >，即</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >Out of Vocabulary</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >；</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="margin-left: 0cm; line-height: 150%; mso-list: l2 level1 lfo4"
>
  <![if !supportLists]><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 'Times New Roman';
      "
      ><span style="mso-list: Ignore"
        >C.<span style="font: 7pt 'Times New Roman'"
          >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </span></span
      ></span
    ></b
  ><![endif]><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >标点符号、数字词和字母词等标为</span
  ><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >“NA”</span
    ></b
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >，即</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >Not Applied</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >，无法查询等级；</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="margin-left: 0cm; line-height: 150%; mso-list: l2 level1 lfo4"
>
  <![if !supportLists]><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 'Times New Roman';
      "
      ><span style="mso-list: Ignore"
        >D.<span style="font: 7pt 'Times New Roman'"
          >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </span></span
      ></span
    ></b
  ><![endif]><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >人名、地名和专名等如不在词表内，则标为</span
  ><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >“NE”</span
    ></b
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >，即</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >Name Entity</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >，同时不参与词汇指标计算。</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  style="margin-top: 7.8pt; mso-para-margin-top: 0.5gd; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: '微软雅黑', sans-serif;
        mso-bidi-font-family: 'Times New Roman';
      "
      >2.3</span
    ></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: '微软雅黑', sans-serif;
        mso-bidi-font-family: 'Times New Roman';
      "
      >文本标注功能说明<span lang="EN-US"><o:p></o:p></span></span
  ></b>
</p>

<p
  class="MsoListParagraph"
  style="
    margin-left: 18pt;
    text-indent: -18pt;
    mso-char-indent-count: 0;
    line-height: 150%;
    mso-list: l11 level1 lfo6;
  "
>
  <![if !supportLists]><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 'Times New Roman';
      "
      ><span style="mso-list: Ignore"
        >A.<span style="font: 7pt 'Times New Roman'"
          >&nbsp;&nbsp;&nbsp;
        </span></span
      ></span
    ></b
  ><![endif]><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: 宋体;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
      "
      >标注等级</span
    ></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      ><o:p></o:p></span
  ></b>
</p>

<p class="MsoListParagraph" style="line-height: 150%">
  <span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >词语等级信息参考《国际中文教育中文水平等级标准》词汇表（后文简称《新标准》词表），该表共收录</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
    11092 </span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >个词语，包括一级</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
    500</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >词、二级</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
    772</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >词、三级</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
    973</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >词、四级</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
    1000</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >词、五级</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
    1071</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >词、六级</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
    1140</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >词、</span
  ><span
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
  </span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >七至九级</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
    5636 </span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >词。</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="
    margin-left: 18pt;
    text-indent: -18pt;
    mso-char-indent-count: 0;
    line-height: 150%;
    mso-list: l11 level1 lfo6;
  "
>
  <![if !supportLists]><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 'Times New Roman';
      "
      ><span style="mso-list: Ignore"
        >B.<span style="font: 7pt 'Times New Roman'"
          >&nbsp;&nbsp;&nbsp;
        </span></span
      ></span
    ></b
  ><![endif]><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: 宋体;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
      "
      >同形词等级消歧</span
    ></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      ><o:p></o:p></span
  ></b>
</p>

<p class="MsoListParagraph" style="line-height: 150%">
  <span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >《新标准》词表收录了</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >128</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >个同形词，其中大多数分属不同等级，例如，“白”（形容词）属于一级，而“白”（副词）属于三级，如果仅在分词后进行词表匹配，则无法区分同形词的不同等级。为解决该问题，本工具利用词性、拼音等特征实现了级别自动消歧，如下例所示：</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="
    margin-left: 39.95pt;
    mso-para-margin-left: 1.71gd;
    text-indent: -22pt;
    mso-char-indent-count: 0;
    line-height: 150%;
    mso-list: l13 level1 lfo7;
  "
>
  <![if !supportLists]><span
    lang="EN-US"
    style="
      font-family: Wingdings;
      mso-fareast-font-family: Wingdings;
      mso-bidi-font-family: Wingdings;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    ><span style="mso-list: Ignore"
      >➢<span style="font: 7pt 'Times New Roman'">&nbsp; </span></span
    ></span
  ><![endif]><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >那</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/r_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >块</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/q_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >墙</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/n_2<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >刷</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/v_4<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >得</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/u_2<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >非常</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/d_1<span style="mso-spacerun: yes">  </span></span
  ><b
    ><span
      style="
        font-family: 宋体;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
        color: #4472c4;
        mso-themecolor: accent1;
        background: yellow;
        mso-highlight: yellow;
      "
      >白</span
    ></b
  ><b
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
        color: #4472c4;
        mso-themecolor: accent1;
        background: yellow;
        mso-highlight: yellow;
      "
      >/a_1</span
    ></b
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    ><span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >。</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/<span class="SpellE">wp_NA</span><span style="mso-spacerun: yes">  </span
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="
    margin-left: 39.95pt;
    mso-para-margin-left: 1.71gd;
    text-indent: -22pt;
    mso-char-indent-count: 0;
    line-height: 150%;
    mso-list: l13 level1 lfo7;
  "
>
  <![if !supportLists]><span
    lang="EN-US"
    style="
      font-family: Wingdings;
      mso-fareast-font-family: Wingdings;
      mso-bidi-font-family: Wingdings;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    ><span style="mso-list: Ignore"
      >➢<span style="font: 7pt 'Times New Roman'">&nbsp; </span></span
    ></span
  ><![endif]><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >我</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/r_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >不</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/d_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >想</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/v_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >再</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/d_1<span style="mso-spacerun: yes">  </span></span
  ><b
    ><span
      style="
        font-family: 宋体;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
        color: #4472c4;
        mso-themecolor: accent1;
        background: yellow;
        mso-highlight: yellow;
      "
      >白</span
    ></b
  ><b
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
        color: #4472c4;
        mso-themecolor: accent1;
        background: yellow;
        mso-highlight: yellow;
      "
      >/d_3</span
    ></b
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    ><span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >跑</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/v_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >一</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/m_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >趟</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/q_6<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >了</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/u_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >。</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/<span class="SpellE">wp_NA</span><span style="mso-spacerun: yes">  </span
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="
    margin-left: 18pt;
    text-indent: -18pt;
    mso-char-indent-count: 0;
    line-height: 150%;
    mso-list: l11 level1 lfo6;
  "
>
  <![if !supportLists]><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 'Times New Roman';
      "
      ><span style="mso-list: Ignore"
        >C.<span style="font: 7pt 'Times New Roman'"
          >&nbsp;&nbsp;&nbsp;
        </span></span
      ></span
    ></b
  ><![endif]><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: 宋体;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
      "
      >扩充词表</span
    ></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      ><o:p></o:p></span
  ></b>
</p>

<p
  class="MsoNormal"
  style="text-indent: 21pt; mso-char-indent-count: 2; line-height: 150%"
>
  <span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >对于《新标准》词表未收录的词语，可根据语素的形式和意义对其是否真正超纲进行判定。如下图所示，在文本标注工具中选择“新标准等级（含扩充词表）”后，会提供基于扩充词表的标注结果，词语</span
  ><span style="font-family: 宋体; mso-bidi-font-family: 'Times New Roman'"
    >后加<b style="mso-bidi-font-weight: normal"
      ><span lang="EN-US">“*”</span></b
    >以示区分，如下两例所示：<span lang="EN-US"><o:p></o:p></span
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="
    margin-left: 39.95pt;
    mso-para-margin-left: 1.71gd;
    text-indent: -22pt;
    mso-char-indent-count: 0;
    line-height: 150%;
    mso-list: l13 level1 lfo7;
  "
>
  <![if !supportLists]><span
    lang="EN-US"
    style="
      font-family: Wingdings;
      mso-fareast-font-family: Wingdings;
      mso-bidi-font-family: Wingdings;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    ><span style="mso-list: Ignore"
      >➢<span style="font: 7pt 'Times New Roman'">&nbsp; </span></span
    ></span
  ><![endif]><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: 宋体;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
        color: #4472c4;
        mso-themecolor: accent1;
        background: yellow;
        mso-highlight: yellow;
      "
      >这个</span
    ></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
        color: #4472c4;
        mso-themecolor: accent1;
        background: yellow;
        mso-highlight: yellow;
      "
      >*/r_1</span
    ></b
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    ><span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >苹果</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/n_3<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >看</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/v_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >起来</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/v_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >非常</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/d_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >新鲜</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/a_4<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >。</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/<span class="SpellE">wp_NA</span> <o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="
    margin-left: 39.95pt;
    text-indent: 0cm;
    mso-char-indent-count: 0;
    line-height: 150%;
  "
>
  <span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >注：《新标准》词表未收录</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >“</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >这个</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >”</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >，但</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >“</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >这</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >”</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >与</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >“</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >个</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >”</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >同为一级词，且</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >“</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >这个</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >”</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >的词义可由其语素推理得到，因此扩充词表将其标记为一级，</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="
    margin-left: 39.95pt;
    mso-para-margin-left: 1.71gd;
    text-indent: -22pt;
    mso-char-indent-count: 0;
    line-height: 150%;
    mso-list: l13 level1 lfo7;
  "
>
  <![if !supportLists]><span
    lang="EN-US"
    style="
      font-family: Wingdings;
      mso-fareast-font-family: Wingdings;
      mso-bidi-font-family: Wingdings;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    ><span style="mso-list: Ignore"
      >➢<span style="font: 7pt 'Times New Roman'">&nbsp; </span></span
    ></span
  ><![endif]><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >我们</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/r_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >在</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/p_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >北京</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/ns_1<span style="mso-spacerun: yes">  </span></span
  ><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: 宋体;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
        color: #4472c4;
        mso-themecolor: accent1;
        background: yellow;
        mso-highlight: yellow;
      "
      >玩</span
    ></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
        color: #4472c4;
        mso-themecolor: accent1;
        background: yellow;
        mso-highlight: yellow;
      "
      >*/v_1</span
    ></b
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    ><span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >了</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/u_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >三</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/m_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >天</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/q_1<span style="mso-spacerun: yes">  </span></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >。</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    >/<span class="SpellE">wp_NA</span><span style="mso-spacerun: yes">  </span
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoListParagraph"
  style="
    margin-left: 39.95pt;
    text-indent: 0cm;
    mso-char-indent-count: 0;
    line-height: 150%;
  "
>
  <span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >注：《新标准》词表收录了“玩儿”（一级），据此将“玩”标记为一级。</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: #4472c4;
      mso-themecolor: accent1;
    "
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  align="left"
  style="text-align: left; mso-pagination: widow-orphan"
>
  <b
    ><span
      lang="EN-US"
      style="
        font-size: 14pt;
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      ><o:p>&nbsp;</o:p></span
    ></b
  >
</p>

<p
  class="MsoListParagraph"
  style="
    margin-left: 18pt;
    text-indent: -18pt;
    mso-char-indent-count: 0;
    line-height: 150%;
    mso-list: l4 level1 lfo8;
  "
>
  <![if !supportLists]><b
    ><span
      lang="EN-US"
      style="
        font-size: 14pt;
        line-height: 150%;
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 'Times New Roman';
      "
      ><span style="mso-list: Ignore"
        >3.<span style="font: 7pt 'Times New Roman'"
          >&nbsp;&nbsp;&nbsp;
        </span></span
      ></span
    ></b
  ><![endif]><b
    ><span
      style="
        font-size: 14pt;
        line-height: 150%;
        font-family: '微软雅黑', sans-serif;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
      "
      >词表生成与词汇丰富性指标分析</span
    ></b
  ><b
    ><span
      lang="EN-US"
      style="
        font-size: 14pt;
        line-height: 150%;
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 微软雅黑;
      "
      ><o:p></o:p></span
  ></b>
</p>

<p
  class="MsoNormal"
  style="margin-top: 7.8pt; mso-para-margin-top: 0.5gd; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: '微软雅黑', sans-serif;
        mso-bidi-font-family: 'Times New Roman';
      "
      >3.1
    </span></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: '微软雅黑', sans-serif;
        mso-bidi-font-family: 'Times New Roman';
      "
      >使用说明<span lang="EN-US"><o:p></o:p></span></span
  ></b>
</p>

<p
  class="MsoNormal"
  style="text-indent: 21.4pt; mso-char-indent-count: 2; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >Step1</span
    ></b
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >: </span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >点击</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >“</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >选择文件</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >”</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >上传</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >txt</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >格式文件，支持上传多个文件进行批量处理，上传文件限定最长</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: red;
    "
    >100</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: red;
    "
    >万字符</span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 宋体;
      color: red;
    "
    >/</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
      color: red;
    "
    >文件</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >；</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  style="text-indent: 21.4pt; mso-char-indent-count: 2; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >Step2</span
    ></b
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >: </span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >点击</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >“</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >保存文件</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >”</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >指定输出文件位置，默认结果保存为</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >xlsx</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >格式表格文件；</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  style="text-indent: 21.4pt; mso-char-indent-count: 2; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >Step3</span
    ></b
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >: </span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >点击</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >“</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >词表生成</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >”</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >或者</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >“</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >指标分析</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >”</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >运行程序，程序运行进度在底部状态栏显示。程序处理速度约</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >1</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >万字</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >/</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >秒（与系统配置有关），如需处理较大规模语料，请耐心关注状态栏提示，运行过程中切勿点击其他按钮。</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  style="margin-top: 7.8pt; mso-para-margin-top: 0.5gd; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: '微软雅黑', sans-serif;
        mso-bidi-font-family: 'Times New Roman';
      "
      >3.2
    </span></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: '微软雅黑', sans-serif;
        mso-bidi-font-family: 'Times New Roman';
      "
      >词表生成功能<span lang="EN-US"><o:p></o:p></span></span
  ></b>
</p>

<p
  class="MsoNormal"
  style="text-indent: 21pt; mso-char-indent-count: 2; line-height: 150%"
>
  <span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >本工具可基于《新标准》词表或《新标准》词表（含扩充词表）生成各等级词表，以表格形式输出文件名、词语、词性、级别等信息。</span
  ><span
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
    <span lang="EN-US"><o:p></o:p></span
  ></span>
</p>

<p
  class="MsoNormal"
  style="margin-top: 7.8pt; mso-para-margin-top: 0.5gd; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: '微软雅黑', sans-serif;
        mso-bidi-font-family: 'Times New Roman';
      "
      >3.3
    </span></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: '微软雅黑', sans-serif;
        mso-bidi-font-family: 'Times New Roman';
      "
      >词汇丰富性指标分析功能<span lang="EN-US"><o:p></o:p></span></span
  ></b>
</p>

<p
  class="MsoNormal"
  style="text-indent: 21pt; mso-char-indent-count: 2; line-height: 150%"
>
  <a name="OLE_LINK1"></a
  ><a name="OLE_LINK2"
    ><span style="mso-bookmark: OLE_LINK1"
      ><span
        style="
          font-family: 宋体;
          mso-ascii-font-family: 'Times New Roman';
          mso-hansi-font-family: 'Times New Roman';
          mso-bidi-font-family: 'Times New Roman';
        "
        >该功能支持基于《新标准》词表或其扩充词表对各等级词语数量和比例进行分析，供测量词汇复杂度参考，此外，还提供了多维度的词汇多样性和词汇密度</span
      ></span
    ></a
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >测量。</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  style="margin-top: 7.8pt; mso-para-margin-top: 0.5gd; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >3.3.1
    </span></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: 宋体;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
      "
      >《新标准》词表指标</span
    ></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      ><o:p></o:p></span
  ></b>
</p>

<p
  class="MsoNormal"
  style="text-indent: 21pt; mso-char-indent-count: 2; line-height: 150%"
>
  <span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >本工具提供基于新标准词表的词汇复杂度指标，并包含多等级的量化指标分析，如中高级、中级及以上（包括超纲词）、高级及以上（包括超纲词）等不同组别，共</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >80</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >个（具体指标可参考附录</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >A</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >）。</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  style="margin-top: 7.8pt; mso-para-margin-top: 0.5gd; line-height: 150%"
>
  <b style="mso-bidi-font-weight: normal"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >3.3.2
    </span></b
  ><b style="mso-bidi-font-weight: normal"
    ><span
      style="
        font-family: 宋体;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
      "
      >词汇多样性和词汇密度指标</span
    ></b
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  align="left"
  style="
    text-align: left;
    text-indent: 21pt;
    mso-char-indent-count: 2;
    line-height: 150%;
  "
>
  <span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >本工具提供多维度的词汇多样性和词汇密度测量，共</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >11</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >个（具体指标可参考附录</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >B</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >）。传统的</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >TTR</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >和</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >RTTR</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >等指标容易受到文本长度影响，难以提供可靠的测量结果，根据</span
  ><span class="SpellE"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >Zenker</span
    ></span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
    &amp; Kyle (2021)</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >的研究，我们集成了</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >MATTR</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >、</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >HDD</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >、</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >MLTD</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >等方法</span
  ><a style="mso-footnote-id: ftn1" href="#_ftn1" name="_ftnref1" title=""
    ><span class="MsoFootnoteReference"
      ><span
        lang="EN-US"
        style="
          font-family: 'Times New Roman', serif;
          mso-fareast-font-family: 宋体;
        "
        ><span style="mso-special-character: footnote"
          ><![if !supportFootnotes]><span class="MsoFootnoteReference"
            ><span
              lang="EN-US"
              style="
                font-size: 10.5pt;
                mso-bidi-font-size: 12pt;
                font-family: 'Times New Roman', serif;
                mso-fareast-font-family: 宋体;
                mso-ansi-language: EN-US;
                mso-fareast-language: ZH-CN;
                mso-bidi-language: AR-SA;
              "
              >[1]</span
            ></span
          ><![endif]></span
        ></span
      ></span
    ></a
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >，在样本长度存在差异时也能提供稳定可靠的测量结果。</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  align="center"
  style="text-align: center; line-height: 150%"
>
  <span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 微软雅黑;
      mso-no-proof: yes;
    "
    ><!--[if gte vml 1
      ]><v:shape
        id="图片_x0020_2"
        o:spid="_x0000_i1025"
        type="#_x0000_t75"
        style="
          width: 321pt;
          height: 310pt;
          visibility: visible;
          mso-wrap-style: square;
        "
      >
        <v:imagedata
          src="images/image002.png"
          o:title=""
        /> </v:shape><!
    [endif]--><![if !vml]><img
      border="0"
      width="321"
      height="310"
      src="images/image002.png"
      v:shapes="图片_x0020_2"
    /><![endif]></span
  ><span
    lang="EN-US"
    style="
      font-family: 'Times New Roman', serif;
      mso-fareast-font-family: 微软雅黑;
    "
    ><o:p></o:p
  ></span>
</p>

<p class="MsoNormal">
  <span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >注：</span
  ><span class="SpellE"
    ><span
      lang="EN-US"
      style="
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 宋体;
      "
      >Zenker</span
    ></span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
  >
    &amp; Kyle</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >（</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >2021</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >）发现在</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >50</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >到</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >200</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >词的英语作文中，</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >MATTR</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >、</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >HD-D</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >、</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >MTLD</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >这三项指标受文本长度的影响较小。</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p class="MsoNormal" align="left" style="text-align: left; line-height: 150%">
  <span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p>&nbsp;</o:p></span
  >
</p>

<p
  class="MsoNormal"
  align="left"
  style="
    text-align: left;
    text-indent: 21pt;
    mso-char-indent-count: 2;
    line-height: 150%;
  "
>
  <span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >如果在您的研究中使用了</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >CLRA</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >工具，欢迎参考和引用：</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p
  class="MsoNormal"
  align="left"
  style="
    text-align: left;
    text-indent: 21pt;
    mso-char-indent-count: 2;
    line-height: 150%;
  "
>
  <span
    lang="EN-US"
    style="font-family: 仿宋; mso-bidi-font-family: 'Times New Roman'"
    >[1] </span
  ><span style="font-family: 仿宋; mso-bidi-font-family: 'Times New Roman'"
    >徐云洁<span lang="EN-US">, </span>王兆基<span lang="EN-US">, </span
    >胡韧奋<span lang="EN-US">. </span
    >基于新标准的汉语词汇复杂度自动分析工具及其应用<span lang="EN-US">. </span
    >第七届汉语中介语语料库建设与应用国际学术讨论会<span lang="EN-US"
      >. 2021.<o:p></o:p></span
  ></span>
</p>

<p
  class="MsoNormal"
  align="left"
  style="
    text-align: left;
    text-indent: 21pt;
    mso-char-indent-count: 2;
    line-height: 150%;
  "
>
  <span
    lang="EN-US"
    style="font-family: 仿宋; mso-bidi-font-family: 'Times New Roman'"
    >[2] </span
  ><span style="font-family: 仿宋; mso-bidi-font-family: 'Times New Roman'"
    >徐云洁<span lang="EN-US">, </span>胡韧奋<span lang="EN-US">. </span
    >汉语词汇丰富性的自动分析研究<span lang="EN-US">. </span
    >数字人文与阅读分级学术研讨会<span lang="EN-US">. 2021.<o:p></o:p></span
  ></span>
</p>

<p class="MsoNormal" align="left" style="text-align: left; line-height: 150%">
  <span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p>&nbsp;</o:p></span
  >
</p>

<p
  class="MsoNormal"
  align="left"
  style="
    text-align: left;
    text-indent: 21pt;
    mso-char-indent-count: 2;
    line-height: 150%;
  "
>
  <span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >CLRA</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >将持续迭代和更新，并集成更多丰富的功能，如果您对</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    >CLRA</span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >研发有任何问题或建议，欢迎与我们联系：</span
  ><span lang="EN-US"
    ><a href="mailto:crystalxu@mail.bnu.edu.cn"
      ><span
        style="
          font-family: 'Times New Roman', serif;
          mso-fareast-font-family: 宋体;
        "
        >crystalxu@mail.bnu.edu.cn</span
      ></a
    ></span
  ><span
    style="
      font-family: 宋体;
      mso-ascii-font-family: 'Times New Roman';
      mso-hansi-font-family: 'Times New Roman';
      mso-bidi-font-family: 'Times New Roman';
    "
    >。</span
  ><span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p></o:p
  ></span>
</p>

<p class="MsoNormal" align="left" style="text-align: left; line-height: 150%">
  <span
    lang="EN-US"
    style="font-family: 'Times New Roman', serif; mso-fareast-font-family: 宋体"
    ><o:p>&nbsp;</o:p></span
  >
</p>

<p class="MsoNormal">
  <b
    ><span
      style="
        font-size: 14pt;
        font-family: '微软雅黑', sans-serif;
        mso-ascii-font-family: 'Times New Roman';
        mso-hansi-font-family: 'Times New Roman';
        mso-bidi-font-family: 'Times New Roman';
        color: black;
        mso-themecolor: text1;
      "
      >附录：词汇维度分析指标类型介绍</span
    ></b
  ><b
    ><span
      lang="EN-US"
      style="
        font-size: 14pt;
        font-family: 'Times New Roman', serif;
        mso-fareast-font-family: 微软雅黑;
        color: black;
        mso-themecolor: text1;
      "
      ><o:p></o:p></span
  ></b>
</p>

<p
  class="MsoNormal"
  align="left"
  style="
    margin-top: 18pt;
    margin-right: 0cm;
    margin-bottom: 12pt;
    margin-left: 0cm;
    text-align: left;
    mso-pagination: widow-orphan;
    mso-outline-level: 4;
  "
>
  <b
    ><span
      lang="EN-US"
      style="
        mso-bidi-font-size: 10.5pt;
        font-family: 宋体;
        mso-bidi-font-family: 'Segoe UI';
        color: #1f2328;
        mso-font-kerning: 0pt;
      "
      >A.
    </span></b
  ><b
    ><span
      style="
        mso-bidi-font-size: 10.5pt;
        font-family: 宋体;
        mso-bidi-font-family: 'Segoe UI';
        color: #1f2328;
        mso-font-kerning: 0pt;
      "
      >新标准等级词表指标（<span lang="EN-US">80</span>个）<span lang="EN-US"
        ><o:p></o:p></span></span
  ></b>
</p>

<table
  class="MsoNormalTable"
  border="1"
  cellspacing="0"
  cellpadding="0"
  style="
    border-collapse: collapse;
    border: none;
    mso-border-alt: solid windowtext 0.5pt;
    mso-yfti-tbllook: 1184;
    mso-padding-alt: 0cm 0cm 0cm 0cm;
    mso-border-insideh: 0.5pt solid windowtext;
    mso-border-insidev: 0.5pt solid windowtext;
  "
>
  <thead>
    <tr style="mso-yfti-irow: 0; mso-yfti-firstrow: yes">
      <td
        width="66"
        style="
          width: 49.4pt;
          border: solid windowtext 1pt;
          mso-border-alt: solid windowtext 0.5pt;
          padding: 4.5pt 9.75pt 4.5pt 9.75pt;
        "
      >
        <p
          class="MsoNormal"
          align="center"
          style="text-align: center; mso-pagination: widow-orphan"
        >
          <b
            ><span
              style="
                mso-bidi-font-size: 10.5pt;
                font-family: 宋体;
                mso-bidi-font-family: 宋体;
                mso-font-kerning: 0pt;
              "
              >编号<span lang="EN-US"><o:p></o:p></span></span
          ></b>
        </p>
      </td>
      <td
        width="246"
        style="
          width: 184.2pt;
          border: solid windowtext 1pt;
          border-left: none;
          mso-border-left-alt: solid windowtext 0.5pt;
          mso-border-alt: solid windowtext 0.5pt;
          padding: 4.5pt 9.75pt 4.5pt 9.75pt;
        "
      >
        <p
          class="MsoNormal"
          align="center"
          style="text-align: center; mso-pagination: widow-orphan"
        >
          <b
            ><span
              style="
                mso-bidi-font-size: 10.5pt;
                font-family: 宋体;
                mso-bidi-font-family: 宋体;
                mso-font-kerning: 0pt;
              "
              >指标<span lang="EN-US"><o:p></o:p></span></span
          ></b>
        </p>
      </td>
      <td
        style="
          border: solid windowtext 1pt;
          border-left: none;
          mso-border-left-alt: solid windowtext 0.5pt;
          mso-border-alt: solid windowtext 0.5pt;
          padding: 4.5pt 9.75pt 4.5pt 9.75pt;
        "
      >
        <p
          class="MsoNormal"
          align="center"
          style="text-align: center; mso-pagination: widow-orphan"
        >
          <b
            ><span
              style="
                mso-bidi-font-size: 10.5pt;
                font-family: 宋体;
                mso-bidi-font-family: 宋体;
                mso-font-kerning: 0pt;
              "
              >描述<span lang="EN-US"><o:p></o:p></span></span
          ></b>
        </p>
      </td>
    </tr>
  </thead>
  <tr style="mso-yfti-irow: 1">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >1<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_sum_of_words</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >词形数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 2">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >2<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_first_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >一级词（词形）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 3">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >3<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_first_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >一级词（词形）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 4">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >4<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_first_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >一级词（词形）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 5">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >5<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_second_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >二级词（词形）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 6">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >6<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_second_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >二级词（词形）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 7">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >7<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_second_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >二级词（词形）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 8">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >8<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_third_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >三级词（词形）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 9">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >9<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_third_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >三级词（词形）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 10">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >10<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_third_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >三级词（词形）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 11">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >11<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_fourth_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四级词（词形）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 12">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >12<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_fourth_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四级词（词形）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 13">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >13<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_fourth_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四级词（词形）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 14">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >14<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_fifth_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >五级词（词形）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 15">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >15<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_fifth_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >五级词（词形）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 16">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >16<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_fifth_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >五级词（词形）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 17">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >17<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_sixth_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >六级词（词形）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 18">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >18<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_sixth_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >六级词（词形）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 19">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >19<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_sixth_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >六级词（词形）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 20">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >20<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_high_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >七<span lang="EN-US">-</span>九级词（词形）数量<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 21">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >21<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_high_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >七<span lang="EN-US">-</span>九级词（词形）占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 22">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >22<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_high_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >七<span lang="EN-US">-</span>九级词（词形）开根占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 23">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >23<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_elementary_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >一<span lang="EN-US">-</span>三级词（词形）数量<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 24">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >24<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_elementary_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >一<span lang="EN-US">-</span>三级词（词形）占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 25">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >25<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_elementary_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >一<span lang="EN-US">-</span>三级词（词形）开根占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 26">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >26<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_medium_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>六级词（词形）数量<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 27">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >27<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_medium_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>六级词（词形）占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 28">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >28<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_medium_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>六级词（词形）开根占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 29">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >29<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_medium&amp;high_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>九级词（词形）数量<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 30">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >30<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_medium&amp;high_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>九级词（词形）占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 31">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >31<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_medium&amp;high_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>九级词（词形）开根占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 32">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >32<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_out_of_voc</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >超纲词（词形）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 33">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >33<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_out_of_voc_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >超纲词（词形）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 34">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >34<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_out_of_voc_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >超纲词（词形）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 35">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >35<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_medium_and_above</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>九级及超纲词（词形）数量<span
            lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 36">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >36<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_medium_and_above_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>九级及超纲词（词形）占比<span
            lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 37">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >37<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_medium_and_above_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>九级及超纲词（词形）开根占比<span
            lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 38">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >38<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_high_and_above</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >七<span lang="EN-US">-</span>九级及超纲词（词形）数量<span
            lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 39">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >39<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_high_and_above_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >七<span lang="EN-US">-</span>九级及超纲词（词形）占比<span
            lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 40">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >40<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >token_high_and_above_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >七<span lang="EN-US">-</span>九级及超纲词（词形）开根占比<span
            lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 41">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >41<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_sum_of_words</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >词种数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 42">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >42<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_first_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >一级词（词种）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 43">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >43<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_first_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >一级词（词种）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 44">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >44<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_first_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >一级词（词种）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 45">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >45<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_second_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >二级词（词种）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 46">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >46<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_second_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >二级词（词种）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 47">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >47<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_second_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >二级词（词种）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 48">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >48<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_third_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >三级词（词种）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 49">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >49<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_third_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >三级词（词种）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 50">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >50<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_third_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >三级词（词种）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 51">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >51<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_fourth_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四级词（词种）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 52">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >52<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_fourth_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四级词（词种）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 53">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >53<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_fourth_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四级词（词种）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 54">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >54<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_fifth_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >五级词（词种）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 55">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >55<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_fifth_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >五级词（词种）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 56">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >56<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_fifth_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >五级词（词种）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 57">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >57<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_sixth_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >六级词（词种）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 58">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >58<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_sixth_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >六级词（词种）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 59">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >59<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_sixth_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >六级词（词种）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 60">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >60<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_high_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >七<span lang="EN-US">-</span>九级词（词种）数量<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 61">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >61<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_high_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >七<span lang="EN-US">-</span>九级词（词种）占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 62">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >62<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_high_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >七<span lang="EN-US">-</span>九级词（词种）开根占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 63">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >63<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_elementary_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >一<span lang="EN-US">-</span>三级词（词种）数量<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 64">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >64<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_elementary_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >一<span lang="EN-US">-</span>三级词（词种）占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 65">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >65<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_elementary_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >一<span lang="EN-US">-</span>三级词（词种）开根占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 66">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >66<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_medium_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>六级词（词种）数量<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 67">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >67<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_medium_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>六级词（词种）占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 68">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >68<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_medium_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>六级词（词种）开根占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 69">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >69<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_medium&amp;high_level</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>九级词（词种）数量<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 70">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >70<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_medium&amp;high_level_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>九级词（词种）占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 71">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >71<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_medium&amp;high_level_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>九级词（词种）开根占比<span lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 72">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >72<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_out_of_voc</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >超纲词（词种）数量<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 73">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >73<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_out_of_voc_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >超纲词（词种）占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 74">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >74<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_out_of_voc_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >超纲词（词种）开根占比<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 75">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >75<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_medium_and_above</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>九级及超纲词（词种）数量<span
            lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 76">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >76<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_medium_and_above_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>九级及超纲词（词种）占比<span
            lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 77">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >77<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_medium_and_above_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >四<span lang="EN-US">-</span>九级及超纲词（词种）开根占比<span
            lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 78">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >78<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_high_and_above</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >七<span lang="EN-US">-</span>九级及超纲词（词种）数量<span
            lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 79">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >79<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_high_and_above_ratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >七<span lang="EN-US">-</span>九级及超纲词（词种）占比<span
            lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 80; mso-yfti-lastrow: yes">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >80<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span class="SpellE"
          ><span
            lang="EN-US"
            style="
              mso-bidi-font-size: 10.5pt;
              font-family: 宋体;
              mso-bidi-font-family: 宋体;
              mso-font-kerning: 0pt;
            "
            >type_high_and_above_rootratio</span
          ></span
        ><span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          ><o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >七<span lang="EN-US">-</span>九级及超纲词（词种）开根占比<span
            lang="EN-US"
            ><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
</table>

<p
  class="MsoNormal"
  align="left"
  style="
    margin-top: 18pt;
    margin-right: 0cm;
    margin-bottom: 12pt;
    margin-left: 0cm;
    text-align: left;
    mso-pagination: widow-orphan;
    mso-outline-level: 4;
  "
>
  <b
    ><span
      lang="EN-US"
      style="
        mso-bidi-font-size: 10.5pt;
        font-family: 宋体;
        mso-bidi-font-family: 'Segoe UI';
        color: #1f2328;
        mso-font-kerning: 0pt;
      "
      >B.
    </span></b
  ><b
    ><span
      style="
        mso-bidi-font-size: 10.5pt;
        font-family: 宋体;
        mso-bidi-font-family: 'Segoe UI';
        color: #1f2328;
        mso-font-kerning: 0pt;
      "
      >词汇多样性和词汇密度指标（<span lang="EN-US">11</span>个）<span
        lang="EN-US"
        ><o:p></o:p></span></span
  ></b>
</p>

<table
  class="MsoNormalTable"
  border="1"
  cellspacing="0"
  cellpadding="0"
  style="
    border-collapse: collapse;
    border: none;
    mso-border-alt: solid windowtext 0.5pt;
    mso-yfti-tbllook: 1184;
    mso-padding-alt: 0cm 0cm 0cm 0cm;
    mso-border-insideh: 0.5pt solid windowtext;
    mso-border-insidev: 0.5pt solid windowtext;
  "
>
  <thead>
    <tr style="mso-yfti-irow: 0; mso-yfti-firstrow: yes">
      <td
        style="
          border: solid windowtext 1pt;
          mso-border-alt: solid windowtext 0.5pt;
          padding: 4.5pt 9.75pt 4.5pt 9.75pt;
        "
      >
        <p
          class="MsoNormal"
          align="center"
          style="text-align: center; mso-pagination: widow-orphan"
        >
          <b
            ><span
              style="
                mso-bidi-font-size: 10.5pt;
                font-family: 宋体;
                mso-bidi-font-family: 宋体;
                mso-font-kerning: 0pt;
              "
              >编号<span lang="EN-US"><o:p></o:p></span></span
          ></b>
        </p>
      </td>
      <td
        style="
          border: solid windowtext 1pt;
          border-left: none;
          mso-border-left-alt: solid windowtext 0.5pt;
          mso-border-alt: solid windowtext 0.5pt;
          padding: 4.5pt 9.75pt 4.5pt 9.75pt;
        "
      >
        <p
          class="MsoNormal"
          align="center"
          style="text-align: center; mso-pagination: widow-orphan"
        >
          <b
            ><span
              style="
                mso-bidi-font-size: 10.5pt;
                font-family: 宋体;
                mso-bidi-font-family: 宋体;
                mso-font-kerning: 0pt;
              "
              >指标<span lang="EN-US"><o:p></o:p></span></span
          ></b>
        </p>
      </td>
      <td
        style="
          border: solid windowtext 1pt;
          border-left: none;
          mso-border-left-alt: solid windowtext 0.5pt;
          mso-border-alt: solid windowtext 0.5pt;
          padding: 4.5pt 9.75pt 4.5pt 9.75pt;
        "
      >
        <p
          class="MsoNormal"
          align="center"
          style="text-align: center; mso-pagination: widow-orphan"
        >
          <b
            ><span
              style="
                mso-bidi-font-size: 10.5pt;
                font-family: 宋体;
                mso-bidi-font-family: 宋体;
                mso-font-kerning: 0pt;
              "
              >描述<span lang="EN-US"><o:p></o:p></span></span
          ></b>
        </p>
      </td>
    </tr>
  </thead>
  <tr style="mso-yfti-irow: 1">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >1<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >CHAR_NUM<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >字数<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 2">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >2<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >WORD_NUM<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >词数<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 3">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >3<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >LEXICAL_TTR<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >Simple TTR<o:p></o:p
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 4">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >4<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >LEXICAL_RTTR<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >Root TTR<o:p></o:p
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 5">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >5<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >LEXICAL_LOG_TTR<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >Log TTR<o:p></o:p
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 6">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >6<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >LEXICAL_MASS_TTR<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >Mass TTR<o:p></o:p
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 7">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >7<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >LEXICAL_MSTTR<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >Mean segmental TTR (MSTTR)<o:p></o:p
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 8">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >8<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >LEXICAL_MATTR<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >Moving average TTR (MATTR)<o:p></o:p
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 9">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >9<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >LEXICAL_HDD<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >Hypergeometric distribution D (HDD)<o:p></o:p
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 10">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >10<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >LEXICAL_MLTD<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >Measure of lexical textual diversity (MTLD)<o:p></o:p
        ></span>
      </p>
    </td>
  </tr>
  <tr style="mso-yfti-irow: 11; mso-yfti-lastrow: yes">
    <td
      style="
        border: solid windowtext 1pt;
        border-top: none;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="center"
        style="text-align: center; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >11<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          lang="EN-US"
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >CONTENT_WORD_DENSITY<o:p></o:p
        ></span>
      </p>
    </td>
    <td
      style="
        border-top: none;
        border-left: none;
        border-bottom: solid windowtext 1pt;
        border-right: solid windowtext 1pt;
        mso-border-top-alt: solid windowtext 0.5pt;
        mso-border-left-alt: solid windowtext 0.5pt;
        mso-border-alt: solid windowtext 0.5pt;
        padding: 4.5pt 9.75pt 4.5pt 9.75pt;
      "
    >
      <p
        class="MsoNormal"
        align="left"
        style="text-align: left; mso-pagination: widow-orphan"
      >
        <span
          style="
            mso-bidi-font-size: 10.5pt;
            font-family: 宋体;
            mso-bidi-font-family: 宋体;
            mso-font-kerning: 0pt;
          "
          >词汇密度<span lang="EN-US"><o:p></o:p></span
        ></span>
      </p>
    </td>
  </tr>
</table>


<hr align="left" size="1" width="33%" />

<p class="MsoFootnoteText">
  <a
    style="mso-footnote-id: ftn1"
    href="#_ftnref1"
    name="_ftn1"
    title=""
    ><span class="MsoFootnoteReference"
      ><span lang="EN-US"
        ><span style="mso-special-character: footnote"
          ><![if !supportFootnotes]><span class="MsoFootnoteReference"
            ><span
              lang="EN-US"
              style="
                font-size: 9pt;
                font-family: DengXian;
                mso-ascii-theme-font: minor-latin;
                mso-fareast-theme-font: minor-fareast;
                mso-hansi-theme-font: minor-latin;
                mso-bidi-font-family: 'Times New Roman';
                mso-bidi-theme-font: minor-bidi;
                mso-ansi-language: EN-US;
                mso-fareast-language: ZH-CN;
                mso-bidi-language: AR-SA;
              "
              >[1]</span
            ></span
          ><![endif]></span
        ></span
      ></span
    ></a
  ><span lang="EN-US">
    <a href="https://github.com/kristopherkyle/lexical_diversity"
      >https://github.com/kristopherkyle/lexical_diversity</a
    >
  </span>
</p>
