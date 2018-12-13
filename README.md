# vue-fixed-table-v2
 基于vue-scroller实现elementUI的固定表格头和列
 
#使用步骤
table--放在vue项目的components文件夹下
ElemTable.vue 引用components下的table组件

#记得在main.js里面 配置
import TableColumn from './components/table/src/table-column';
Vue.component('el-table-column', TableColumn);
