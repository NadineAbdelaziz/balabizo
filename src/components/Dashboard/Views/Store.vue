<template>
    <div class="row">
      <div class="col-md-12">
        <div class="card">
          <paper-table :title="table1.title" :sub-title="table1.subTitle" :data="table1.data" :columns="table1.columns">

          </paper-table>
        </div>
      </div>

    </div>
</template>
<script>
  import PaperTable from 'components/UIComponents/PaperTable.vue'
  const tableColumns = ['Id', 'Name', 'Price', 'CreatedAt', 'UpdatedAt', 'SellerName']
  const tableData = [{
    id: 1,
    name: 'Backpack',
    price: '$30',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Nadine Adel'
  },
  {
    id: 2,
    name: 'Clock',
    price: '$40',
    createdat: '11/2/2018',
    updatedat: '17/4/2018',
    sellername: 'Dona Jaradah'
  },
  {
    id: 3,
    name: 'Laptops',
    price: '$55',
    createdat: '18/9/2018',
    updatedat: '16/2/2018',
    sellername: 'Lina Hany'
  },
  {
    id: 4,
    name: 'Bottles',
    price: '$70',
    createdat: '19/2/2018',
    updatedat: '13/2/2018',
    sellername: 'David Hany'
  },
  {
    id: 5,
    name: 'Clothes',
    price: '$100',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Menna Wael'
  },
  {
    id: 6,
    name: 'Mobiles',
    price: '$110',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Khaled El Shimi'
  },
  {
    id: 7,
    name: 'Pantalon',
    price: '$120',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Youssef Ramy'
  },
  {
    id: 8,
    name: 'sleeves',
    price: '$100',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Sama Walid'
  },
  {
    id: 9,
    name: 'Computers',
    price: '$90',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Liza Charles'
  },
  {
    id: 10,
    name: 'Jackets',
    price: '$90',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Mohamed Saeed'
  },
  {
    id: 11,
    name: 'Bags',
    price: '$80',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Ziad Aly'
  },
  {
    id: 12,
    name: 'Make up',
    price: '$100',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Amr el Arabi'
  },
  {
    id: 13,
    name: 'Clothes',
    price: '$90',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Nourhan Ali'
  },
  {
    id: 14,
    name: 'Shoes',
    price: '$90',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Passant Omar'
  },
  {
    id: 15,
    name: 'Laptops',
    price: '$60',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Mina Ramsis'
  },
  {
    id: 16,
    name: 'PC',
    price: '$90',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Rawan Shehab'
  },
  {
    id: 17,
    name: 'Pull Overs',
    price: '$80',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Samira Mahmoud'
  },
  {
    id: 18,
    name: 'Mobiles',
    price: '$100',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Farah Wael'
  },
  {
    id: 19,
    name: 'Mobiles',
    price: '$90',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Omar Zakaria'
  },
  {
    id: 20,
    name: 'Rings',
    price: '$80',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Nour Mostafa'
  },
  {
    id: 21,
    name: 'Socks',
    price: '$100',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Amr Noaman'
  },
  {
    id: 22,
    name: 'Sleeves',
    price: '$100',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Omar'
  },
  {
    id: 23,
    name: 'Mobiles',
    price: '$100',
    createdat: '15/2/2018',
    updatedat: '16/2/2018',
    sellername: 'Sameh Sonbol'
  }
]

  export default {
    components: {
      PaperTable
    },
    data () {
      return {
        table1: {
          title: 'BI T-17',
          subTitle: ' Amazon ',
          columns: [...tableColumns],
          data: [...tableData]
        },
        table2: {
          title: 'Table on Plain Background',
          subTitle: 'Here is a subtitle for this table',
          columns: [...tableColumns],
          data: [...tableData]
        }
      }
    }
  }

</script>
<style>

</style>
