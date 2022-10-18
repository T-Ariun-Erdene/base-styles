# Burenscore base-styles
Энэхүү repository нь Burenscore project-д ашиглагдах style-уудыг агуулна.

## Ажиллах заавар
1. Style-уудаа оруулна.
2. `npm run postcss` кодыг ажиллуулан style > main.scss файл үүсгэнэ.
3. `sass style/main.scss style/converted/converted.css` кодыг ажиллуулан style > converted > converted.css файл үүсгэнэ.
4. `npx tailwindcss -i ./style/converted/converted.css -o ./style/main.css` кодыг ажиллуулан raw css файл бий болгоно. Гэхдээ style > converted > main.css файл дээр `@tailwind base;
   @tailwind components;
   @tailwind utilities;` мөрүүд заавал орсон байх ёстой.


## Ашигласан CDN технологи
[jsdelivr](https://www.jsdelivr.com/)