<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 400" font-family="Segoe UI, Arial, sans-serif">
  <defs>
    <marker id="arrow4" markerWidth="10" markerHeight="7" refX="10" refY="3.5" orient="auto">
      <polygon points="0 0, 10 3.5, 0 7" fill="#555"/>
    </marker>
    <marker id="arrow4o" markerWidth="10" markerHeight="7" refX="10" refY="3.5" orient="auto">
      <polygon points="0 0, 10 3.5, 0 7" fill="#f57c00"/>
    </marker>
  </defs>
  
  <!-- Фон -->
  <rect width="700" height="400" fill="#fafafa" rx="12"/>
  
  <!-- Заголовок -->
  <text x="350" y="30" text-anchor="middle" font-size="16" font-weight="bold" fill="#333">Два модуса преквалиа</text>
  
  <!-- Преквалиа 1-го порядка (рамка) -->
  <rect x="40" y="60" width="280" height="180" rx="10" fill="none" stroke="#c2185b" stroke-width="2" stroke-dasharray="4,2"/>
  <text x="180" y="85" text-anchor="middle" font-size="13" font-weight="bold" fill="#880e4f">Преквалиа 1-го порядка</text>
  
  <!-- Содержание преквалиа-1 -->
  <rect x="70" y="105" width="220" height="110" rx="8" fill="#fce4ec" stroke="#c2185b" stroke-width="2"/>
  <text x="180" y="130" text-anchor="middle" font-size="12" fill="#880e4f">Сырой потенциал</text>
  <text x="180" y="155" text-anchor="middle" font-size="11" font-style="italic" fill="#ad1457">нет Архитектуры</text>
  <text x="180" y="175" text-anchor="middle" font-size="11" font-style="italic" fill="#ad1457">нет Среды</text>
  <text x="180" y="195" text-anchor="middle" font-size="11" font-style="italic" fill="#ad1457">нет Знака</text>
  
  <!-- Преквалиа 2-го порядка (рамка) -->
  <rect x="380" y="60" width="280" height="180" rx="10" fill="none" stroke="#f57c00" stroke-width="2" stroke-dasharray="4,2"/>
  <text x="520" y="85" text-anchor="middle" font-size="13" font-weight="bold" fill="#e65100">Преквалиа 2-го порядка</text>
  
  <!-- Содержание преквалиа-2 -->
  <rect x="410" y="105" width="220" height="110" rx="8" fill="#fff3e0" stroke="#f57c00" stroke-width="2"/>
  <text x="520" y="130" text-anchor="middle" font-size="12" fill="#e65100">Внутрицикловое состояние</text>
  <text x="520" y="155" text-anchor="middle" font-size="11" font-style="italic" fill="#ef6c00">Архитектура есть</text>
  <text x="520" y="175" text-anchor="middle" font-size="11" font-style="italic" fill="#ef6c00">Среда есть</text>
  <text x="520" y="195" text-anchor="middle" font-size="11" font-style="italic" fill="#ef6c00">резонанс временно прерван</text>
  
  <!-- Стрелка перехода -->
  <line x1="320" y1="150" x2="378" y2="150" stroke="#555" stroke-width="2" marker-end="url(#arrow4)"/>
  <text x="350" y="140" text-anchor="middle" font-size="10" fill="#333">первый</text>
  <text x="350" y="165" text-anchor="middle" font-size="10" fill="#333">Знак</text>
  
  <!-- Кенозис (самозамыкание преквалиа-2) -->
  <path d="M 520 242 C 520 310, 520 310, 520 242" fill="none" stroke="#f57c00" stroke-width="2"/>
  <path d="M 630 160 C 680 160, 680 260, 632 215" fill="none" stroke="#f57c00" stroke-width="2" marker-end="url(#arrow4o)"/>
  <text x="670" y="220" text-anchor="middle" font-size="10" fill="#f57c00">кенозис</text>
  
  <!-- Общее свойство -->
  <rect x="150" y="290" width="400" height="50" rx="8" fill="#f5f5f5" stroke="#999" stroke-width="1"/>
  <text x="350" y="312" text-anchor="middle" font-size="12" fill="#555">Общее: высокая энтропия, суперпозиция, отсутствие формы</text>
  <text x="350" y="330" text-anchor="middle" font-size="11" font-style="italic" fill="#777">Различие: онтологический статус компонентов</text>
</svg>
