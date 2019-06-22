<template>
  <el-table
    :data="tableData"
    style="width: 100%">
    <el-table-column
      prop="id_01"
      label="星期一"
      width="150">
    </el-table-column>
    <el-table-column
      prop="id_02"
      label="星期二"
      width="150">
    </el-table-column>
    <el-table-column
      prop="id_03"
      label="星期三"
      width="150">
    </el-table-column>
    <el-table-column
      prop="id_04"
      label="星期四"
      width="150">
    </el-table-column>
    <el-table-column
      prop="id_05"
      label="星期五"
      width="150">
    </el-table-column>
  </el-table>
</template>

  <script>
    export default {
      data() {
        return {
          tableData: [
          	{
          		id_01:"数学",
          		id_02:"语文",
          		id_03:"英语",
          		id_04:"数学",
          		id_05:"英语",
          		
          	},{
          		id_01:"数学",
          		id_02:"语文",
          		id_03:"英语",
          		id_04:"数学",
          		id_05:"英语",
          		
          	},{
          		id_01:"数学",
          		id_02:"语文",
          		id_03:"英语",
          		id_04:"数学",
          		id_05:"英语",
          		
          	},{
          		id_01:"数学",
          		id_02:"语文",
          		id_03:"英语",
          		id_04:"数学",
          		id_05:"英语",
          		
          	},
          	
          ]
        }
      }
    }
  </script>