if(hh <= 13 && mm <= 0){ // ช่วงเวลาเช็คอิน
document.getElementById(“cin”).classList.remove(‘invisible’);
}else if(hh >= 17 && mm >= 0){ // ช่วงเวลาเช็คเอ้าท์
document.getElementById(“cout”).classList.remove(‘invisible’);
}else{
alert(“ไม่สามารถเช็คอิน/เอาท์ได้ในช่วงเวลา 13.00–17.00”);
liff.closeWindow();
}


ต้องแก้ไขใน script
var channelToken
var latx = “9.0202447”;
var longx = “99.1767025”;
กำหนด lat/long จุดเช็ค
if(xdist > 2){ //ปรับระยะห่าง
เมื่อทำทุกอย่างครบแล้ว สร้าง rich menu > link > liff url
