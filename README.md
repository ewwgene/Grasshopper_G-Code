
# [ewwgene.github.io /](https://ewwgene.github.io/) [_PROGRAMMING_ /](https://ewwgene.github.io/PROGRAMMING) Grasshopper_G-Code

[![Grasshopper_G-Code](/100.jpg)](https://ewwgene.github.io/Grasshopper_G-Code/Carousel)<br> <a id="111" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#111"><img src="https://ewwgene.github.io/Grasshopper_G-Code/111.jpg" height="66"></a> <a id="113" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#113"><img src="https://ewwgene.github.io/Grasshopper_G-Code/113.jpg" height="66"></a> <a id="115" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#115"><img src="https://ewwgene.github.io/Grasshopper_G-Code/115.jpg" height="66"></a> <a id="117" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#117"><img src="https://ewwgene.github.io/Grasshopper_G-Code/117.jpg" height="66"></a> <a id="119" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#119"><img src="https://ewwgene.github.io/Grasshopper_G-Code/119.jpg" height="66"></a> <a id="121" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#121"><img src="https://ewwgene.github.io/Grasshopper_G-Code/121.jpg" height="66"></a> <a id="text">&#160;</a>



Алгоритм создания _G-Code_ для станка с ЧПУ в среде _`RHINOCEROS_3D`_. Референсом служит растровое изображение - фотография _.jpg_.

### Making — _2018.04-2018.06._
<a id="411m" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#411m"><img src="https://ewwgene.github.io/Grasshopper_G-Code/Making/411.jpg" height="66"></a> <a id="413m" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#413m"><img src="https://ewwgene.github.io/Grasshopper_G-Code/Making/413.jpg" height="66"></a> <a id="415m" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#415m"><img src="https://ewwgene.github.io/Grasshopper_G-Code/Making/415.jpg" height="66"></a> <a id="417m" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#417m"><img src="https://ewwgene.github.io/Grasshopper_G-Code/Making/417.jpg" height="66"></a> <a id="419m" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#419m"><img src="https://ewwgene.github.io/Grasshopper_G-Code/Making/419.jpg" height="66"></a> <a id="421m" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#421m"><img src="https://ewwgene.github.io/Grasshopper_G-Code/Making/421.jpg" height="66"></a>  

_`RHINOCEROS_3D`_ _`GRASSHOPPER`_ _`CIMCO_EDIT`_ _`INKSCAPE`_  _**`CNC_MILLING`**_ 

Импорт изображения в _`GRASSHOPPER`_, нахождение на изображении зон с максимальной контрасностью, котоорые могут означать границы предметов, и создание вогруг этих зон _Сил_ отталкивания, притягивания или закручивания. Сгенерированные _Силы_ используются для прокладки пути движения инструмента станка с ЧПУ, в моем случае - это фрезер. Траектория движение фрезы в горизонтальной плоскости _XY_ стремиться _прилипнуть_ к границам предметов на фотографии, а глубина _Z_ зависит от яркости участка - чем место на фотографии темнее - тем глубже в заготовку погружается инструмент. Траектория пути движения инструмента в _`GRASSHOPPER`_ представляет собой простые линии и кривые, которые преобразуются в _G-Code_ с помощью набора алгоритмов _GRUNBLAU 3 Axis G-CODE Generator by [Brian Oltrogge](https://www.grunblau.com/contact)_ &#129309;

<a id="301" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#301"><img src="https://ewwgene.github.io/Grasshopper_G-Code/301.jpg" height="66"></a> <a id="303" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#303"><img src="https://ewwgene.github.io/Grasshopper_G-Code/303.jpg" height="66"></a> <a id="305" href="https://ewwgene.github.io/Grasshopper_G-Code/Carousel/#305"><img src="https://ewwgene.github.io/Grasshopper_G-Code/305.jpg" height="66"></a> 

_`PROGRAMMING`_ _`ALGORITHM`_ 

<br> 

### [ABOUT /](https://ewwgene.github.io/ABOUT)
### [MAIL_TO:](mailto:r0cam@me.com)