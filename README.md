# Collection of scripts for my daily use

> [!WARNING]
> No guarantee or warranty; Use with caution!

## Tips for writing scripts for Status Bar

I am using [JetBrainsMono font](https://www.jetbrains.com/lp/mono/) in my status bar. It has icons for all my usecases.

I use [this site](https://www.nerdfonts.com/cheat-sheet) to quickly checkout the unicode of icons

To see icons in action, please run the following in your terminal
```bash
echo "<span font='JetBrainsMono 50'> 
        <span foreground='#9eaaee'> \uf015 </span> <span foreground='#ff6e00'> \Uf1970 </span> <span foreground='#9eaaee'> \uf015 </span>
        <span foreground='#00ff7f'> Home Sweet Home </span>
      </span>" > test.pango
pango-view --markup test.pango
 ```

