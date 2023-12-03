# rime-double-pinyin-flynorman
小鹤双拼norman布局

## 安裝

本方案依賴於
  - [prelude](https://github.com/rime/rime-prelude): 基礎配置
  - [essay](https://github.com/rime/rime-essay): 八股文
  - [朙月拼音](https://github.com/rime/rime-luna-pinyin): luna-pinyin
  - [双拼](https://github.com/rime/rime-double-pinyin): 双拼

rime-dependency(对新版rime可能无效了)
  - 2021-09-04 前的rime依赖，直接复制过来

trime-layout-norman
  - trime输入法norman键盘布局

# 基于雾凇拼音修改
git@github.com:guoxuedong/rime-ice.git


# ~/Library/Rime 下是用户级别的配置文件，下边的文件都直接放在这个路径下就可以了
git clone git@github.com:rime/plum.git
bash rime-install prelude
bash rime-install essay
bash rime-install luna-pinyin
bash rime-install double-pinyin

# 修改 double_pinyin_flypy.schema.yaml，支持 norman 布局
# speller/algebra:  都替换
# translator/preedit_format：都替换
# reverse_lookup 可以删掉
# translators/reverse_lookup_translator 可以删掉

