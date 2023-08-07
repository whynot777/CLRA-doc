<header class="el-header">
  <h2 style="text-align: center">CLRA中文词汇丰富性分析器 V1.0</h2>
  <p style="text-align: center">2023/08</p>
</header>

<main class="el-main">
  <div style="font-size: 15px; padding: 0px 200px">
    <p>
        <b>CLRA工具</b> (<span style="color: rgb(203, 27, 69)">C</span
        >hinese <span style="color: rgb(203, 27, 69)">L</span>exical
        <span style="color: rgb(203, 27, 69)">R</span>ichness
        <span style="color: rgb(203, 27, 69)">A</span>nalyzer)
      由北京师范大学科研团队研发，旨在为中文教育领域的教材、学生作文或口语产出提供词汇维度的量化分析支持，当前版本可提供如下两项功能。
    </p>
    <h3>1. 文本标注工具</h3>
    文本标注工具可处理10万字以内的文本，包含分词、标注词性、标注新标准等级、标注新标准等级（含扩充词表）等四个功能。
    其中，新标准等级信息参考《国际中文教育中文水平等级标准》中的词汇表，该表共收录 11092 个词语，包括一级 500词、二级 772词、三级 973词、四级 1000词、五级
    1071词、六级 1140词、 七至九级 5636 词。新标准等级（含扩充词表）则是对大纲未收录的词语，根据语素对其是否超纲进行判定，并在词语后标“*”以示区分。
    对于词表中的128个同形或兼类词，本工具可运用词性、拼音等信息进行级别消歧。
    <h3>2. 词汇丰富性分析</h3>
    在词汇丰富性分析模式下，支持批量上传文件。词表生成功能可基于新标准词表生成各等级词表，以表格为形式输出各级别具体词汇。
    指标分析功能可从词汇多样性、词汇密度、基于新标准词表等多个角度对语篇的词汇量化指标进行分析输出,该分析模式下只能选中一种词表/指标类型。（注：词汇多样性工具来自：https://github.com/kristopherkyle/lexical_diversity）
    <h3>附录：词汇丰富性分析指标类型介绍</h3>
    <h4>A. 新标准等级词表指标（80个）</h4>
    <div
      class="el-table--fit el-table--striped el-table--scrollable-x el-table--enable-row-hover el-table--enable-row-transition el-table el-table--layout-fixed is-scrolling-left"
      data-prefix="el"
      style="width: fit-content; margin: 0px auto"
    >
      <div class="el-table__inner-wrapper">
        <div class="el-table__body-wrapper">
          <div class="el-scrollbar">
            <div class="el-scrollbar__wrap el-scrollbar__wrap--hidden-default">
              <div
                class="el-scrollbar__view"
                style="display: inline-block; vertical-align: middle"
              >
                <table
                  class="el-table__body"
                  cellspacing="0"
                  cellpadding="0"
                  border="0"
                  style="table-layout: fixed; width: 490px"
                >
                  <colgroup>
                    <col name="el-table_1_column_1" width="60" />
                    <col name="el-table_1_column_2" width="180" />
                    <col name="el-table_1_column_3" width="250" />
                  </colgroup>
                  <thead class="">
                    <tr class="">
                      <th
                        class="el-table_1_column_1 is-leaf el-table__cell"
                        colspan="1"
                        rowspan="1"
                      >
                        <div class="cell">编号<!----><!----></div>
                      </th>
                      <th
                        class="el-table_1_column_2 is-leaf el-table__cell"
                        colspan="1"
                        rowspan="1"
                      >
                        <div class="cell">指标<!----><!----></div>
                      </th>
                      <th
                        class="el-table_1_column_3 is-leaf el-table__cell"
                        colspan="1"
                        rowspan="1"
                      >
                        <div class="cell">描述<!----><!----></div>
                      </th>
                    </tr>
                  </thead>
                  <!--v-if-->
                  <tbody>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->1</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_sum_of_words</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->词形数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->2</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_first_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->一级词（词形）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->3</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_first_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->一级词（词形）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->4</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_first_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->一级词（词形）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->5</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_second_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->二级词（词形）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->6</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_second_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->二级词（词形）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->7</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_second_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->二级词（词形）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->8</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_third_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->三级词（词形）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->9</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_third_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->三级词（词形）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->10</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_third_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->三级词（词形）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->11</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_fourth_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四级词（词形）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->12</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_fourth_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四级词（词形）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->13</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_fourth_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四级词（词形）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->14</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_fifth_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->五级词（词形）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->15</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_fifth_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->五级词（词形）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->16</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_fifth_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->五级词（词形）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->17</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_sixth_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->六级词（词形）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->18</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_sixth_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->六级词（词形）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->19</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_sixth_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->六级词（词形）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->20</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_high_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->七-九级词（词形）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->21</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_high_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->七-九级词（词形）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->22</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_high_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->七-九级词（词形）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->23</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_elementary_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->一-三级词（词形）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->24</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_elementary_level_ratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->一-三级词（词形）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->25</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_elementary_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->一-三级词（词形）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->26</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_medium_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四-六级词（词形）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->27</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_medium_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四-六级词（词形）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->28</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_medium_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四-六级词（词形）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->29</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_medium&amp;high_level
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四-九级词（词形）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->30</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_medium&amp;high_level_ratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四-九级词（词形）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->31</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_medium&amp;high_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四-九级词（词形）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->32</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_out_of_voc</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->超纲词（词形）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->33</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_out_of_voc_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->超纲词（词形）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->34</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_out_of_voc_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->超纲词（词形）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->35</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_medium_and_above</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->四-九级及超纲词（词形）数量
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->36</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_medium_and_above_ratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->四-九级及超纲词（词形）占比
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->37</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_medium_and_above_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->四-九级及超纲词（词形）开根占比
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->38</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->token_high_and_above</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->七-九级及超纲词（词形）数量
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->39</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_high_and_above_ratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->七-九级及超纲词（词形）占比
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->40</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->token_high_and_above_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->七-九级及超纲词（词形）开根占比
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->41</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_sum_of_words</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->词种数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->42</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_first_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->一级词（词种）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->43</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_first_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->一级词（词种）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->44</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_first_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->一级词（词种）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->45</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_second_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->二级词（词种）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->46</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_second_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->二级词（词种）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->47</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_second_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->二级词（词种）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->48</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_third_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->三级词（词种）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->49</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_third_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->三级词（词种）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->50</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_third_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->三级词（词种）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->51</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_fourth_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四级词（词种）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->52</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_fourth_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四级词（词种）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->53</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_fourth_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四级词（词种）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->54</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_fifth_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->五级词（词种）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->55</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_fifth_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->五级词（词种）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->56</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_fifth_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->五级词（词种）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->57</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_sixth_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->六级词（词种）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->58</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_sixth_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->六级词（词种）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->59</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_sixth_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->六级词（词种）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->60</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_high_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->七-九级词（词种）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->61</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_high_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->七-九级词（词种）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->62</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_high_level_rootratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->七-九级词（词种）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->63</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_elementary_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->一-三级词（词种）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->64</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_elementary_level_ratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->一-三级词（词种）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->65</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_elementary_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->一-三级词（词种）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->66</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_medium_level</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四-六级词（词种）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->67</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_medium_level_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四-六级词（词种）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->68</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_medium_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四-六级词（词种）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->69</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_medium&amp;high_level
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四-九级词（词种）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->70</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_medium&amp;high_level_ratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四-九级词（词种）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->71</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_medium&amp;high_level_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->四-九级词（词种）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->72</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_out_of_voc</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->超纲词（词种）数量</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->73</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_out_of_voc_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->超纲词（词种）占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->74</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_out_of_voc_rootratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->超纲词（词种）开根占比</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->75</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_medium_and_above</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->四-九级及超纲词（词种）数量
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->76</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_medium_and_above_ratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->四-九级及超纲词（词种）占比
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->77</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_medium_and_above_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->四-九级及超纲词（词种）开根占比
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->78</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_high_and_above</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->七-九级及超纲词（词种）数量
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->79</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->type_high_and_above_ratio</div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->七-九级及超纲词（词种）占比
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_1_column_1 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->80</div>
                      </td>
                      <td
                        class="el-table_1_column_2 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->type_high_and_above_rootratio
                        </div>
                      </td>
                      <td
                        class="el-table_1_column_3 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->七-九级及超纲词（词种）开根占比
                        </div>
                      </td>
                    </tr>
                  </tbody>
                </table>
                <!--v-if--><!--v-if-->
              </div>
            </div>
            <div class="el-scrollbar__bar is-horizontal" style="display: none">
              <div
                class="el-scrollbar__thumb"
                style="transform: translateX(0%); width: 20px"
              ></div>
            </div>
            <div class="el-scrollbar__bar is-vertical" style="display: none">
              <div
                class="el-scrollbar__thumb"
                style="transform: translateY(0%)"
              ></div>
            </div>
          </div>
        </div>
        <!--v-if--><!--v-if-->
      </div>
      <div class="el-table__column-resize-proxy" style="display: none"></div>
    </div>
    <h4>B. 词汇多样性和词汇密度指标（13个）</h4>
    <div
      class="el-table--fit el-table--striped el-table--scrollable-x el-table--enable-row-hover el-table--enable-row-transition el-table el-table--layout-fixed is-scrolling-left"
      data-prefix="el"
      style="width: fit-content; margin: 0px auto"
    >
      <div class="el-table__inner-wrapper">
        <div class="el-table__body-wrapper">
          <div class="el-scrollbar">
            <div class="el-scrollbar__wrap el-scrollbar__wrap--hidden-default">
              <div
                class="el-scrollbar__view"
                style="display: inline-block; vertical-align: middle"
              >
                <table
                  class="el-table__body"
                  cellspacing="0"
                  cellpadding="0"
                  border="0"
                  style="table-layout: fixed; width: 490px"
                >
                  <colgroup>
                    <col name="el-table_2_column_4" width="60" />
                    <col name="el-table_2_column_5" width="180" />
                    <col name="el-table_2_column_6" width="250" />
                  </colgroup>
                  <thead class="">
                    <tr class="">
                      <th
                        class="el-table_2_column_4 is-leaf el-table__cell"
                        colspan="1"
                        rowspan="1"
                      >
                        <div class="cell">编号<!----><!----></div>
                      </th>
                      <th
                        class="el-table_2_column_5 is-leaf el-table__cell"
                        colspan="1"
                        rowspan="1"
                      >
                        <div class="cell">指标<!----><!----></div>
                      </th>
                      <th
                        class="el-table_2_column_6 is-leaf el-table__cell"
                        colspan="1"
                        rowspan="1"
                      >
                        <div class="cell">描述<!----><!----></div>
                      </th>
                    </tr>
                  </thead>
                  <!--v-if-->
                  <tbody>
                    <tr class="el-table__row">
                      <td
                        class="el-table_2_column_4 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->1</div>
                      </td>
                      <td
                        class="el-table_2_column_5 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->CHAR_NUM</div>
                      </td>
                      <td
                        class="el-table_2_column_6 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->字数</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_2_column_4 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->2</div>
                      </td>
                      <td
                        class="el-table_2_column_5 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->WORD_NUM</div>
                      </td>
                      <td
                        class="el-table_2_column_6 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->词数</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_2_column_4 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->3</div>
                      </td>
                      <td
                        class="el-table_2_column_5 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->LEXICAL_TTR</div>
                      </td>
                      <td
                        class="el-table_2_column_6 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->Simple TTR</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_2_column_4 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->4</div>
                      </td>
                      <td
                        class="el-table_2_column_5 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->LEXICAL_RTTR</div>
                      </td>
                      <td
                        class="el-table_2_column_6 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->Root TTR</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_2_column_4 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->5</div>
                      </td>
                      <td
                        class="el-table_2_column_5 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->LEXICAL_LOG_TTR</div>
                      </td>
                      <td
                        class="el-table_2_column_6 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->Log TTR</div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_2_column_4 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->6</div>
                      </td>
                      <td
                        class="el-table_2_column_5 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->LEXICAL_MASS_TTR</div>
                      </td>
                      <td
                        class="el-table_2_column_6 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->Mass TTR</div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_2_column_4 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->7</div>
                      </td>
                      <td
                        class="el-table_2_column_5 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->LEXICAL_MSTTR</div>
                      </td>
                      <td
                        class="el-table_2_column_6 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->Mean segmental TTR (MSTTR)
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_2_column_4 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->8</div>
                      </td>
                      <td
                        class="el-table_2_column_5 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->LEXICAL_MATTR</div>
                      </td>
                      <td
                        class="el-table_2_column_6 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->Moving average TTR (MATTR)
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_2_column_4 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->9</div>
                      </td>
                      <td
                        class="el-table_2_column_5 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->LEXICAL_HDD</div>
                      </td>
                      <td
                        class="el-table_2_column_6 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->Hypergeometric distribution D (HDD)
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_2_column_4 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->10</div>
                      </td>
                      <td
                        class="el-table_2_column_5 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->LEXICAL_MLTD</div>
                      </td>
                      <td
                        class="el-table_2_column_6 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->Measure of lexical textual diversity (MTLD)
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_2_column_4 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->11</div>
                      </td>
                      <td
                        class="el-table_2_column_5 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->LEXICAL_MLTD_MA_WRAP</div>
                      </td>
                      <td
                        class="el-table_2_column_6 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->Measure of lexical textual diversity (moving
                          average, wrap)
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row el-table__row--striped">
                      <td
                        class="el-table_2_column_4 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->12</div>
                      </td>
                      <td
                        class="el-table_2_column_5 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->LEXICAL_MLTD_MA_BID</div>
                      </td>
                      <td
                        class="el-table_2_column_6 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell">
                          <!---->Measure of lexical textual diversity (moving
                          average, bi-directional)
                        </div>
                      </td>
                    </tr>
                    <tr class="el-table__row">
                      <td
                        class="el-table_2_column_4 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->13</div>
                      </td>
                      <td
                        class="el-table_2_column_5 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->CONTENT_WORD_DENSITY</div>
                      </td>
                      <td
                        class="el-table_2_column_6 el-table__cell"
                        rowspan="1"
                        colspan="1"
                      >
                        <div class="cell"><!---->词汇密度</div>
                      </td>
                    </tr>
                  </tbody>
                </table>
                <!--v-if--><!--v-if-->
              </div>
            </div>
            <div class="el-scrollbar__bar is-horizontal" style="display: none">
              <div
                class="el-scrollbar__thumb"
                style="transform: translateX(0%); width: 20px"
              ></div>
            </div>
            <div class="el-scrollbar__bar is-vertical" style="display: none">
              <div
                class="el-scrollbar__thumb"
                style="transform: translateY(0%)"
              ></div>
            </div>
          </div>
        </div>
        <!--v-if--><!--v-if-->
      </div>
      <div class="el-table__column-resize-proxy" style="display: none"></div>
    </div>
    <p>
      如果您有任何问题或建议，欢迎联系开发者徐云洁（crystalxu@mail.bnu.edu.cn）。
    </p>
  </div>
</main>
