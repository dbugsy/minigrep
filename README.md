# minigrep
Learning rust: [minigrep project](https://doc.rust-lang.org/book/ch12-00-an-io-project.html)

Program accepts 2 arguments, a filename and a query. It will return all lines from the file that contain the query.

Given a file 'poem.txt':

```
// poem.txt

I'm nobody! Who are you?
Are you nobody, too?
Then there's a pair of us - don't tell!
They'd banish us, you know.

How dreary to be somebody!
How public, like a frog
To tell your name the livelong day
To an admiring bog!

```

The query `./target/debug/minigrep body poem.txt` will return:

```
I'm nobody! Who are you?
Are you nobody, too?
How dreary to be somebody!
```

