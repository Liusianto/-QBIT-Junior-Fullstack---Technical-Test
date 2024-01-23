# -QBIT-Junior-Fullstack---Technical-Test

Nomor 1
const fruitNames = fruits.map(fruit => fruit.fruitName);
console.log(fruitNames);

Nomor 2
const fruitTypes = Array.from(new Set(fruits.map(fruit => fruit.fruitType)));
console.log(fruitTypes.length);

Nomor 3
fruitTypes.forEach(type => {
  const fruitsInType = fruits.filter(fruit => fruit.fruitType === type).map(fruit => fruit.fruitName);
  console.log(type, fruitsInType);
});

Nomor 4
Nama dari fruitName yang mirip seperti Apel dengan apel dan Kurma dengan KURMA dapat diganti menjadi fruitName yang berbeda untuk lebih mudah membedakan jenis fruitName. Serta untuk fruitId dapat diubah pada fruitId 5 sehingga dapat membedakan antara Jeruk Bali, KURMA, dan Salak.

Nomor 5
fruitTypes.forEach(type => {
  const totalStock = fruits.filter(fruit => fruit.fruitType === type).reduce((sum, fruit) => sum + fruit.stock, 0);
  console.log(type, totalStock);
});

function countComments(comments: IComment[]): number {
  let count = 0;
  for (let comment of comments) {
    count++;
    if (comment.replies) {
      count += countComments(comment.replies);
    }
  }
  return count;
}

console.log(countComments(comments));
Nomor 6
Website UMKM Katering bernamakan Happy Catering.
