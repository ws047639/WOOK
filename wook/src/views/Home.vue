<template>
  <div class="home">
   <div class="container">
     <div class="row">
       <div class="col-6">
         <div class="img-block">
           <img src="https://hexschool.github.io/THE_F2E_Design/week5-comic%20viewer/assets/comic%20cover.png">
         </div>
       </div>
       <div class="col-6">
        <div class="comic-title">
          MY HEXSCHOOL
        </div>
        <div class="comic-detail">
          <div class="detail-group">
            <strong>Genres</strong>
            <span>Fusce/vehicula/dolor</span>
          </div>
          <div class="detail-group">
            <strong>Author</strong>
            <span>Namae Shiranai</span>
          </div>
          <div class="detail-group">
            <strong>status</strong>
            <span>ongoing</span>
          </div>
          <div class="detail-group">
            <strong>Rate</strong>
            <span>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
            </span>
          </div>
          <div class="detail-group">
            <strong>Summary</strong>
            <p>If your banker breaks, you snap; if your apothecary by mistake sends you poison in your pills, you die.</p>
            <p>Therefore, I say, I saw that this situation of mine was the precise situation of every mortal that has this Siamese connexion with a plurality of other mortals. </p>
          </div>
        </div>
       </div>
     </div>
     <div class="row">
       <div class="col-12">
         <div class="chapters">
           <div class="chap-title">
             All Chapters
           </div>
           <ul>
            <li>Chapter 1: The F2E Challenge STrat!</li>
            <li>Chapter 2: Todo List is GOing Crazy!<span class="new-chap">NEW</span></li>
           </ul>
         </div>
       </div>
     </div>
   </div>
  </div>
</template>

<style  lang="scss" scoped>
.home {
  margin-top: 24px;
}

.img-block{
  min-width: 300px;
  border: 4px solid #000;
  box-sizing: border-box;
  img {
    height: 100%;
    width: 100%;
  }
}

.comic-title {
  background-color: #000;
  color: #fff;
  font-size: 36px;
  font-weight: bold;
  padding: 8px 24px;
  text-align: center;
}

.comic-detail {
  padding: 24px;
  .detail-group {
    margin-top: 8px;
    strong {
      font-size: 16px;
      font-weight: 700;
      line-height: 24px;
      display: inline-block;
      width: 30%;
    }
    span {
      display: inline-block;
      width: 70%;
      font-size: 16px;
      line-height: 24px;
      i {
      margin-right: 10px;
      
    }
    }
    p {
      margin-top: 24px;
    }
    
  }
}

.chapters {
    margin-top: 8px;
    .chap-title {
      display: inline-block;
      font-size: 24px;
      line-height: 28px;
      background-color: #000;
      color: #fff;
    }
}

</style>
