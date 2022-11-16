<template>
  <nav class="navbar navbar-expand-lg bg-transparent navber-custom p-0">
    <div class="container-fluid p-0">
      <form class="search-place">
        <img src="../assets/Svg/Vector.svg" alt="" class="ps-1 search-position">
        <input class="form-control input-field" type="search" placeholder="Search Here ....">
      </form>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto">
          <li class="custom-nav-icon me-5">
            <div>
              <button type="button" class="btn btn-none">
                <img src="../assets/Svg/45-chat.svg" alt="">
                <h1 class="translate-middle badge custom-badge">
                  2
                </h1>
              </button>
            </div>
            <div>
              <button type="button" class="btn btn-none">
                <img src="../assets/Svg/announcement.svg" alt="">
                <h1 class="translate-middle badge custom-badge">
                  2
                </h1>
              </button>
            </div>
            <div class="px-3 py-1">
              <img src="../assets/Svg/Setting.svg" alt="">
            </div>
          </li>
          <div class="nav-item">
            <div class="d-flex align-content-center">
              <div class="image-admin me-4">
              </div>
              <div className="admin-datails">
                <h5>Madison Eve</h5>
                <p>Admin</p>
              </div>
            </div>
          </div>
        </ul>
      </div>
    </div>
  </nav>
</template>
