# 天使动漫一键评分
在天使动漫论坛版块页面里，为所选的帖子进行一键评分（可自行修改默认评分设置）

## 脚本下载地址
https://greasyfork.org/scripts/20839

## 配置项
    /**
     * 配置项
     */
    var Config = {
        // 是否在选择的时候排除已评分的帖子，true：开启；false：关闭
        excludeRatingThreadEnabled: true,
        // 是否在选择的时候排除自己的帖子，true：开启；false：关闭
        excludeMyThreadEnabled: true,
        // 是否在关闭评分结果对话框后自动刷新页面，true：开启；false：关闭
        refreshPageAfterCloseRatingResultDialogEnabled: true,
        // ajax请求的时间间隔（毫秒）
        ajaxInterval: 200,
        // ajax请求的超时时间（毫秒）
        ajaxTimeout: 20000
    };

## 默认评分设置
    /**
     * 默认评分设置
     * 关键字：可通过jQuery选择的dom对象
     * 值：想要设置的预设值
     * @example
     * var DefValueConfig = {
     *     '[name="score1"]': '+1', // 将威望设为+1
     *     '[name="score2"]': '+2', // 将天使币设为+1
     *     '[name="score3"]': '+3', // 将宣传设为+1
     *     '[name="score4"]': '+4', // 将天然设为+1
     *     '[name="score5"]': '+5', // 将腹黑设为+1
     *     '[name="score6"]': '-1', // 将精灵设为-1
     *     '#reason': '很给力', // 将评分理由设为“很给力”
     *     '#highlight_thread': true, // 高亮帖子
     *     '[name="highlight_color"]': '4', // 将帖子高亮颜色设为深绿色
     *     '#highlight_op_1': true, // 将帖子标题设为粗体
     *     '#highlight_op_2': true, // 将帖子标题设为斜体
     *     '#highlight_op_3': true, // 为帖子标题添加下划线
     *     '[name="sendreasonpm"]': true, // 勾选通知作者的复选框
     * };
     */
    var DefValueConfig = {
        '[name="score1"]': '+10',
        '[name="score2"]': '+20',
        '#highlight_thread': true,
        '[name="highlight_color"]': '4',
        '#highlight_op_1': true,
    };

## License
[MIT](http://opensource.org/licenses/MIT)
