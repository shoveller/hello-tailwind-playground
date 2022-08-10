## tailwindcss 를 활용한 간이 개발환경
### 아래의 코드 모음이 필수
```html
    <!-- 플러그인을 포함한 cdn 주소 -->
    <script src="https://cdn.tailwindcss.com?plugins=forms,typography,aspect-ratio,line-clamp"></script>
    <script>
        // tailwind 설정, 없어도 동작에는 문제가 없다
        // 아래의 링크는 기본 설정이다.
        // https://github.com/tailwindlabs/tailwindcss/blob/master/stubs/defaultConfig.stub.js
        tailwind.config = {}
    </script>
    <style type="text/tailwindcss">
        /*임의의 tailwindcss */
        .grid-container {
            @apply grid grid-cols-2 gap-1
        }

        .grid-item {
            @apply flex justify-center items-center bg-orange-100
        }
    </style>
```

