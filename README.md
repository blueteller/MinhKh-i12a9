# MinhKh-i12a9
Vẽ hình tròn hoàn hảo httm
<canvas id="c" width="300" height="300"></canvas>
<script>
const c = document.getElementById('c');
const ctx = c.getContext('2d');
ctx.beginPath();
// vẽ tâm (150.5,150.5) giúp chống aliasing khi stroke 1px
ctx.arc(150.5, 150.5, 100, 0, Math.PI*2);
ctx.lineWidth = 1;
ctx.strokeStyle = '#000';
ctx.stroke();
</script>
