<template>
    <div class="main-div">
  <nav class="navbar">
    <!-- Left Section -->
    <div class="nav-left">
      <img src="../icons/Group.png" alt="Logo" class="logo" />
      <div class="nav-center">
        <p>Events</p>
        <p>Rents</p>
        <p>Jobs</p>
        <p>Sales</p>
      </div>
    </div>

    <!-- Right Section -->
    <div class="nav-right">
      <button class="post-btn">Post Add</button>
      <img src="../icons/Avatar.png" alt="User" class="avatar" />
    </div>
  </nav>
  
  </div>
</template>

<style scoped>
.main-div{
    width: 1,440px;
    height: 80px;
}
.navbar {
  display: flex;
  justify-content: space-between; /* spread left and right sections */
  align-items: center;
  
 width: 1,280px;
 height:  48px;
   padding-top: 16px;
      padding-bottom: 16px;
  padding-left: 80px;
      padding-right: 80px;

}

.nav-left {
  display: flex;
  align-items: center;
  gap: 20px;
}

.logo {
 Width :
118.38px;
 Height: 
28px;

}


.nav-center {
  display: flex;
  gap: 20px;

}

.nav-center p {
  margin: 0;
  font-size: 16px;
  color: #333;
  cursor: pointer;
    font-family: "Inter", sans-serif;
}

.nav-center p:hover {
  color: #004aad;
}

.nav-right {
  display: flex; /* ✅ FIXED */
  align-items: center;
  justify-content: flex-end;
  gap: 24px;
}

 .post-btn {
  background: linear-gradient(90deg, #0134A2, #012779, #3467D5);
  color: #fff;
  border: none;
  /* border-radius: 6px; */
  /* padding: 10px 18px; */
  cursor: pointer;
  transition: 0.3s ease;
font-weight: 500;
   font-family: "Inter", sans-serif;
   line-height: 24px;
   width:106px;
   height: 44px;
    border-radius: 4px;
    border:1px;
}
 

.post-btn:hover {
  opacity: 0.9;
  transform: translateY(-1px);
}

.avatar {
  height: 48px;
  width: 48px;
  border-radius: 200;
 
}
</style>
