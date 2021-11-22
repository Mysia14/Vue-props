<template>
  <div>
    <Header />
<header>
  <h1> Title: {{siteInfo.pageName}} </h1>
  </header>
  <main>
    <h2> A loop of cards </h2>
  <footer>
    <p>&copy; 2021 | {{siteInfo.author}}</p> 
  </footer>
    </div>
</template>
<script>
export default {
  data() {
    return{
      siteInfo: { 
        pageName: "Mysia14 Blog",
        author: "Mysia Santana"
      }, 
      topics: [
        {
          title: "Living La Vida",
          description: "Article about my life",
          category: "blog",
          image: "images/uploads/fall.jpg",

        },
        {
          title: "A life as developer",
          description: "Article about a new career",
          category: "artcile"
        },
        {
          title: "The fear",
          description: "Article about ",
          category: "artcile"
        },
        {title: "Motherhood",
        description: "Article about bein a mom in a foregein country",
        category: "artcile"

        }
      ]
    }
    
  },
}
</script>