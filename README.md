# vue-table-dynamic-sum

English | [简体中文](./README.zh-CN.md)

[vue-table-dynamic-sum](https://github.com/TheoXiong/vue-table-dynamic) is a vue component of dynamic table. It's designed to respond to data changes in real time, and oriented to the runtime.
This fork has new __includeSumInSearch__ parameter.

If true every row that has 'Σ' sign in one of the cells will be included in search.

## Features
- Multiple Select
- Search
- Sort
- Filter
- Pagination
- Edit
- Border
- Stripe
- Highlight
- Column Width
- Configure Header
- Fixed Header
- Fixed Columns
- Slot

## Install
``` 
$   npm install vue-table-dynamic-sum --save
```

## Usage

### Import
```
import VueTableDynamic from 'vue-table-dynamic-sum'
```

### Registration
#### Global registration
```
Vue.use(VueTableDynamic)
```
#### Local registration
```
<script>
export default {
  components: { VueTableDynamic }
}
</script>
```

### Basic Table

Basic table usage

![basic](./docs/images/basic.png)
