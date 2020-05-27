## Tailwind explained

## Challenges
### ch1:design 9 boxes with all shades of blue 20x24 px
1rem = 16px

```
<html>
    <head>
        <link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet">
    </head>
    <body class="bg-gray-200">
        
        <div class="w-5 h-6 bg-blue-100">Text</div>
        <div class="w-5 h-6 bg-blue-200">Text</div>
        <div class="w-5 h-6 bg-blue-300">Text</div>
        <div class="w-5 h-6 bg-blue-400">Text</div>
        <div class="w-5 h-6 bg-blue-500">Text</div>
        <div class="w-5 h-6 bg-blue-600">Text</div>
        <div class="w-5 h-6 bg-blue-700">Text</div>
        <div class="w-5 h-6 bg-blue-800">Text</div>
        <div class="w-5 h-6 bg-blue-900">Text</div>
        
    </body>
</html>
```

### ch2: padding & margin
.{p|m{l|r|t|b}}-{size}

Sizes
0,1,2,3,4,5,6    +1
8,10,12,         +2
16,20,24         +4
32,40,48,56,64   +8

ex. if need padding of 16px, will be p-4

```
<div class="bg-blue-800 w-32 h-32 mb-4 p-4">Text</div>
 <div class="bg-blue-500 w-32 h-32 p-4">Text</div>
```
{p|m{x|y}}-{size}

### ch3