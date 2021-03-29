# CoderX
Bài tập trên CoderX
/**
* Dùng vòng lặp for kiểm tra số nguyên tố.
* @param {number} x Số cần kiểm tra
* @return {boolean} Trả về true nếu là số nguyên tố, ngược lại là false.
*/
function isPrimeNumber(x) {
  if (x < 2) {
    return false;
  }
  if (x === 2){
      return true;
  }
  for (var i = 2; i <= x; i++) {
    if (x % i === 0) {
      return false;
    } else {
      return true;
    }
  }
}
