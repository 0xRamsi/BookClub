## My Book Club - a demo project while learning Scala.

This project has 2 submodules, which are the backend and frontend of a website for a book-club.

This project is really simple, and mostly just my learning Scala.

## How to run the project

### Inside docker

Prerequisites: A working version of docker.

```

```

#### On your machine

Prerequisites: You have on your machine: pnpm, Scala, sbt

```
git clone https://github.com/0xRamsi/BookClub.git
cd BookClub
git submodule init
git submodule update
## Now you should have all the source-code.
cd backend
sbt run
```
Now the backend should be reachable at localhost:8081.

In a new shell
```
cd BookClub/frontend
pnpm install
pnpm start
```

Now you should have it running on http://localhost:8080