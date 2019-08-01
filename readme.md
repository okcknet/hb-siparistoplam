# Hepsiburada Sipariş Toplam Scripti

Hepsiburada Sipariş Toplam


`var a=0;var r=0;var e=document.body.scrollHeight;var n=0;function o(){e=document.body.scrollHeight;if(e!==n){window.scrollTo(0,document.body.scrollHeight);n=document.body.scrollHeight;if(r%4===0){console.log("Data alınıyor, lütfen bekleyiniz...")}}else{a++}r++}function t(){var a=document.getElementsByClassName("order-row__summary__price");var r=0;var e=a.length;for(var n=0;n<a.length;n++){r+=parseFloat(a[n].children[0].textContent.replace(".","").replace(",","."))}alert("Toplam Sipariş Adedi: "+e+"\nToplam Harcama: "+r)}var i=setInterval(function(){if(a<3){o()}else{clearInterval(i);t()}},300);`
