# -QBIT-Junior-Fullstack---Technical-Test

Nomor 1
Apel
Kurma
apel
Manggis
Jeruk Bali
KURMA
Salak

Nomor 2
IMPORT: Apel, Kurma, apel, KURMA.
LOCAL:  Manggis, Jeruk Bali, Salak.

Nomor 3
IMPORT: 10 (Apel) + 20 (Kurma) + 50 (apel) + 20 (KURMA) = 100 buah.
LOCAL:  100 (Manggis) + 10 (Jeruk Bali) + 150 (Salak) = 260 buah.

Nomor 4
Nama dari fruitName yang mirip seperti Apel dengan apel dan Kurma dengan KURMA dapat diganti menjadi fruitName yang berbeda untuk lebih mudah membedakan jenis fruitName. Serta untuk fruitId dapat diubah pada fruitId 5 sehingga dapat membedakan antara Jeruk Bali, KURMA, dan Salak.

Nomor 5
function countComments(comments: IComment[]): number {
  let count = 0;
  for (let comment of comments) {
    count++; // count the comment itself
    if (comment.replies) {
      count += countComments(comment.replies); // recursively count replies
    }
  }
  return count;
}

Nomor 6
Website UMKM Katering bernamakan Happy Catering.
