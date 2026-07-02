━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
 TMUX  prefix: C-a             │  NVIM
───────────────────────────────┼────────────────────────────────────
 SESSIONS                      │  MODES
  o       sessionx picker      │   i / a     insert before / after
  S       choose session       │   I / A     line start / end
  C-d     detach               │   o / O     new line below / above
                               │   jj / jk   → Esc
 WINDOWS                       │  NAVIGATE
  C-c     new window           │   w / b     word fwd / back
  H / L   prev / next          │   0 / $     line start / end
  C-a     last window          │   gg / G    file top / bottom
  r       rename               │   C-d/C-u   ½ page ↓ / ↑
  R       reload config        │   %         jump to match
                               │   C-o/C-i   jump back / forward
 PANES                         │  DELETE  (d = cut)
  s / v   split ↕ / ↔          │   dd        line
  hjkl    navigate panes       │   dw / D    word / to eol
  z       zoom toggle          │   di"/di(   inside " or (
  x / c   kill pane            │   x         char under cursor
  p       float (floax)        │  CHANGE  (delete → insert)

*       sync panes             │   cc / C    line / to eol
  { / }   swap pane ← / →      │   cw        word
  C-o     rotate panes fwd     │   ci"/ci(   inside " or (
                               │
 RESIZE  (repeatable)          │  YANK & PASTE
  , / .   ← / →                │   yy        line
* / =   ↓ / ↑                  │   yw / y$   word / to eol
                               │   p / P     paste after / before
 COPY MODE  (vi)               │
  [       enter copy mode      │  VISUAL
  v       begin selection      │   v / V     char / line select
  y       yank                 │   C-v       block select
                               │  SEARCH & SUB
 OTHER                         │   /pat      search forward
  K       clear pane           │   n / N     next / prev match
  P       pane border toggle   │   *         word under cursor
                               │  CODE
                               │   >> / <<   indent / dedent
                               │   ==        auto-indent line
                               │   J         join lines
                               │   u/C-r/.   undo · redo · repeat
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  hjkl         focus window        shift-hjkl    move window
  1-6          workspace           shift-1-6     → workspace
  tab          back & forth        shift-tab     → next monitor
  ctrl-f       float / tile        ctrl-shift-f  fullscreen
  shift-=/-    resize ±50          /  tiles  ·   ,  accordion
  w  wezterm · o  obsidian · s  slack · z  zen · f  finder
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
