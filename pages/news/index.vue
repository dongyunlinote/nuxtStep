<template>
  <div>
      <h2>News Index page</h2>
      <p>NewsID:{{$route.params.newsId}}</p>
       <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/news/123">News-1</a></li>
        <li><a href="/news/456">News-2</a></li>
        <li><nuxt-link :to="{name:'news-id',params:{id:123}}">News-1 全局路由动画效果</nuxt-link></li>


        <li><nuxt-link :to="{name:'news-id',params:{id:123,title:'jspang.com'}}">News-1 个性meta设置</nuxt-link></li>
        
        <nuxt-link :to="{name:'newsChild'}">跳转到子路由</nuxt-link>
        <a href="/news/newsChild">跳转到子路由</a>

      </ul>
  </div>
</template>