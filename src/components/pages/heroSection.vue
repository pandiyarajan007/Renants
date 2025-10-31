<!-- <template>
    <div class="hero-section">

       <div class="sub-section">
        <div class="hero-content">
        <img src="../icons/Heading.png "/>
        </div>
        <div class="hero-images">
        <img src="../icons/Contents.png"/>
        </div>

       </div>

    </div>
    </template>
    <style scoped>
.hero-section{
background-image: url('../icons/Abstract.png');
  background-size: cover;
  background-position: center; 
  background-repeat: no-repeat; 
  height: 688px;
  display: flex;
  align-items: center;
  justify-content: center;
    background-color:#012779 ; 
}
.sub-section{
    Width :1,280px;
Height :496px;
padding-left: 32px;
padding-right:32px;
gap:64px;
}
.hero-images {
 
  background-size: cover;
  background-position: center;
  height: 768px;
  width:762px;
 
  top:-136px;
}
.hero-content{
    display:flex;
}
</style> -->

<template>
  <div class="hero-section">
    <div class="sub-section">
      <!-- Left side (heading) -->
      <div class="hero-content">
        <img src="../icons/Heading.png" alt="Heading" />
      </div>

      <!-- Right side (main image) -->
      <div class="hero-images">
        <img src="../icons/Contents.png" alt="Contents" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.hero-section {
  background-image: url('../icons/Abstract.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 688px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #012779;
}

/* ✅ Fixing layout of the sub-section */
.sub-section {
  display: flex;              
  align-items: center;         
  justify-content: space-between; 
  width: 1280px;              
  height: 496px;
  padding-top:96px;
  padding-bottom: 96px;
  padding-left:80px;
  gap: 64px;                   
}

/* Left (Heading) */
.hero-content {

  width:660px;
  height:280px;
  gap:40px;

}

/* Right (Image section) */
.hero-images {

  width:492px;
  height:496px;
}

.hero-images img {
  width: 100%;
  height: auto;
  max-width: 762px;
}
</style>
