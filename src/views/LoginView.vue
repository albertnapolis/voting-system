<template>
    <div class="login-container w-100 h-100 d-flex flex-column flex-sm-row aling-items-center justify-content-center ">
        <div class="d-flex align-items-center justify-content-center justify-content-sm-end">
            <div class="logo">
                <img src="../assets/Pasted image 20250322143827.png" alt="logo" class="img-fluid">
            </div>
        </div>
        <div class="d-none d-sm-flex align-items-center justify-content-center">
            <span class="divider gradient-background mx-5 rounded-1 h-25" style="padding: 1px;"></span>
        </div>
        <div class="login-form d-flex align-items-center justify-content-center px-3 px-md-0">
            <form class="col-11">
                <div class="mb-3">
                  <label for="studentID" class="form-label">Student ID</label>
                  <input class="form-control border-2 border-black rounded-1" id="studentID" placeholder="e.g 20116">
                </div>
                <div class="mb-3">
                  <label for="studentPassword" class="form-label">Password</label>
                  <input type="password" class="form-control border-2 border-black rounded-1" id="studentPassword">
                </div>
                <button type="submit" class="btn w-100 rounded-1 text-white shadow" style="background: #800000">Login</button>
            </form>
        </div>
    </div>
</template>