function login() {
    let user = document.getElementById("username").value;
    let pass = document.getElementById("password").value;
    let info = document.getElementById("info");

    if (user === "admin" && pass === "123") {
        document.getElementById("loginPage").classList.add("hidden");
        document.getElementById("mainPage").classList.remove("hidden");
    } else {
        info.innerHTML = "Username atau password salah!";
        info.style.color = "red";
    }
}

function logout() {
    document.getElementById("mainPage").classList.add("hidden");
    document.getElementById("loginPage").classList.remove("hidden");
}
