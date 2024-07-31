Link to the video guide made by ByteGrad: https://www.youtube.com/watch?v=tm70Xa6igbY

Need to run 3 terminals to start project:

1. docker compose up
2. npx prisma studio
3. npm run dev

Issues and solutions:

1. before using the cmd command "docker compose up", you need to open the docker desktop app on your pc (you might need to close your current nextjs instance and then run "docker compose up" again
2. add revalidatePath after task creation to auto update page without refresh
