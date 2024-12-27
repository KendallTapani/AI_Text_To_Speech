This is a neat little Next.js app I put together using Elevenlabs. This does not install the Elevenlabs library, rather, it makes a manual HTTP request, and gets a response MPEG audio file, that is then formatted and played over the browser.

Formatting the HTTP request manually is often more reliable for larger companies, and it's easier to read and see what's going on. I did that it here in TypeScript without any complicated code. 

The app uses generic Next.js, TypeScript, and Tailwind. The main files to check out are the route.ts and text-to-speech.tsx files, which contain most of the code. The rest is generic Nextjs rendering and styling.

For some of the more complicated parts in the route.ts file, I added comments explaining what each individual section is doing.

The end result is quite impressive.

(The API key isn’t active; its normally in a .env)



![Screenshot from 2024-11-25 01-10-43](https://github.com/user-attachments/assets/551c488b-759d-4552-a901-3ab626a61d56)
