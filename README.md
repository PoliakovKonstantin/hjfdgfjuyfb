# hjfdgfjuyfb
db.books.insertMany(
[
{
  title:abc,
  description:qwer,
  authors: 123
},
{
  title:cba,
  description:rewq,
  authors:321
}
]
)
db.books.find(
  {title: abc}
)
db.books.updateOne(
  {id:1}
  {$set: {description:asdafas,authors:nksfdnskdf}}
)
