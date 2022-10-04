External Source:
Body Background:
body {
    --line : #60b4d7;
    --bg: #9ecbce;
  
    background: linear-gradient(135deg, var(--bg) 30%, transparent 30%) -50px 0,
      linear-gradient(225deg, var(--bg) 25%, transparent 25%) -50px 0,
      linear-gradient(315deg, var(--bg) 25%, transparent 25%),
      linear-gradient(45deg, var(--bg) 25%, transparent 25%);
    background-size: 100px 100px;
    background-color: var(--line);
  }