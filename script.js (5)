const reveals = document.querySelectorAll(".reveal");

window.addEventListener("scroll", () => {
reveals.forEach((el)=>{
const windowHeight = window.innerHeight;
const elementTop = el.getBoundingClientRect().top;

if(elementTop < windowHeight - 100){
el.classList.add("active");
}
});
});
document.getElementById("year").textContent=new Date().getFullYear()

function toggleMode(){
document.body.classList.toggle("dark")
}
