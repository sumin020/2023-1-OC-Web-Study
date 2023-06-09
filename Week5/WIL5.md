1. HTML
1) 
 HTML(HyperText Markup Language)은 웹페이지를 기술하기 위한 마크업 언어이다. 웹페이지의 내용과 구조를 담당하는 언어로 태그를 통해 정보를 구조화한다. HTML5 문서는 반드시 <!DOCTYPE html>로 시작하여 문서형식을 HTML5로 지정한다. 
 HTML 요소는 시작 태그와 종료 태그 그리고 그 사이에 위치한 content로 구성된다. HTML document는 요소들의 집합으로 이루어진다. 요소는 중첩될 수 있으며 이때 부자관계로 정보를 구조화한다. html 요소는 웹페이지를 구성하는 모든 요소들을 포함한다, 중첩관계는 들여쓰기를 활용한다.
 content를 가질 수 없는 요소를 빈 요소라고 한다. content를 가질 필요가 없으며 attribute만을 가질 수 있다. br, hr, img, input, link, meta...
 attribute란 요소의 성질, 특징을 정의하는 명세이다. 요소는 attribute를 가질 수 있으며 attribute는 요소에 추가적 정보를 제공하며 시작 태그에 위치해야하고 이름과 값의 쌍을 이룬다. 글로벌 attribute는 모든 HTML 요소가 공통으로 사용할 수 있디. id, class, hidden, lang, style, tabindex, title...

2) 
 시맨틱 태그는 브라우저, 검색엔진, 개발자 모두에게 콘텐츠의 의미를 명확히 설명하는 역할을 한다. 시맨틱 태그에 의해 컴퓨터가 HTML 요소의 의미를 보다 명확히 해석하고 그 데이터를 활용할 수 있는 시맨틱 웹이 실현될 수 있다. 시맨틱 웹이란 웹에 존재하는 수많은 웹페이지들에 메타데이터를 부여하여, 기존의 잡다한 데이터 집합이었던 웹페이지를 ‘의미’와 ‘관련성’을 가지는 거대한 데이터베이스로 구축하고자 하는 발상이다. HTML 요소는  non-simantic 요소, simantic 요소로 구분할 수 있으며 non-simantic 요소는 div, span 등이 있으며 content에 대해 어떤 설명도 하지 않는다. simantic 요소는 form, table, img 등이 있으며 content의 의미를 명확히 설명한다.

3) 
 문서 형식 정의(DTD) 태그는 출력할 웹 페이지의 형식을 브라우저에게 전달한다. 문서의 최상위에 위치한다. html 태그는 모든 HTML 요소의 부모 요소이며 웹페이지에 단 하나만 존재한다. 즉, 모든 요소는 html 요소의 자식 요소이며 html 요소 내부에 기술해야 한다. 
 head 요소는 메타데이터를 포함하기 위한 요소이며 웹페이지에 단 하나만 존재한다. 메타데이터는 HTML 문서의 title, style, link, script에 대한 데이터로 화면에 표시되지 않는다. link 요소에는 외부 리소스와의 연계 정보를 정의한다. script 요소에는 client-side JavaScript를 정의한다. 메타데이터는 브라우저, 검색엔진 등에 의해 사용되며 charset 어트리뷰트는 브라우저가 사용할 문자셋을 정의한다.
 body tag는 HTML 문서의 내용을 나타내며 웹페이지에 단 하나만 존재한다. 메타데이터를 제외한 웹페이지를 구성하는 대부분의 요소가 body 요소 내에 기술된다.

4)
heading 태그는 제목을 나타낼 때 사용하며 h1에서 h6까지의 태그가 있다. 
b는 bold체를 지정한다. strong은 bold체를 지정하고 의미론적 중요성의 의미를 갖는다.
I는 Italic체를 지정한다.
em은 emphasized text를 지정하며 Italic체로 지정하며 의미론적 중요성의 의미를 갖는다.
small은 small text를 지정한다.
mark는 highlighted text를 지정한다.
del은 deleted text를 지정한다.
ins는 inserted text를 지정한다.
p는 단락을 지정한다.
br tag는 강제 개행을 지정하며 빈 요소로 종료태그가 없다.
pre는 형식화된 text를 지정하며 pre 내의 content는 그대로 브라우저에 표시된다.
hr은 수평줄을 삽입한다.

2. CSS
1) 
 CSS(Cascading Style Sheets)는 HTML이나 XML과 같은 구조화 된 문서를 화면, 종이 등에 어떻게 렌더링할 것인지를 정의하기 위한 언어이다. 즉, CSS는 HTML의 각 요소의 style을 정의하여 화면 등에 어떻게 렌더링하면 되는지 브라우저에게 설명하기 위한 언어이다.
 셀렉터로 HTML 요소를 선택하고 {} 내에 프로퍼티(속성)와 값을 지정하는 것으로 다양한 style을 정의할 수 있다. 프로퍼티는 표준 스펙으로 이미 지정되어 있는 것을 사용하여야하며 사용자가 임의로 정의할 수 없다. 프로퍼티의 값은 특정 단위로 지정하여야 한다.
 모든 웹 브라우저는 디폴트 스타일을 가지고 있어 CSS가 없어도 작동한다. 그런데 웹브라우저에 따라 디폴트 스타일이 상이하고 지원하는 tag나 style도 제각각이다. Reset CSS는 기본적인 HTML 요소의 CSS를 초기화하는 용도로 사용한다. 자주 사용되는 Reset CSS로는 Eric Meyer’s reset, normalize.css가 있다.

2)
 style을 적용하고자 하는 HTML 요소를 셀렉터로 특정하고 선택된 요소에 스타일을 정의한다. 전체 셀렉터는 *이며 HTML 문서 내의 모든 요소를 선택한다. 태그 셀렉터는 지정된 태그명을 가지는 요소를 선택한다. ID 셀렉터는 id 어트리뷰트 값을 지정하여 일치하는 요소를 선택한다. 클래스 셀렉터는 class 어트리뷰트 값을 지정하여 일치하는 요소를 선택한다. 어트리뷰트 셀렉터는 지정된 어트리뷰트를 갖는 모든 요소를 선택한다.
 자신의 1 level 상위에 속하는 요소를 부모 요소, 1 level 하위에 속하는 요소를 자손 요소(자식 요소)라한다. 자신보다 n level 하위에 속하는 요소는 후손 요소(하위 요소)라 한다. 후손 셀렉터는 셀렉터A의 모든 후손(하위) 요소 중 셀렉터B와 일치하는 요소를 선택한다. 자손 셀렉터는 셀렉터A의 모든 자식 요소 중 셀렉터B와 일치하는 요소를 선택한다. 형제(동위) 셀렉터는 형제 관계(동위 관계)에서 뒤에 위치하는 요소를 선택할 때 사용한다.
 가상 클래스는 요소의 특정 상태에 따라 스타일을 정의할 때 사용된다.

3) 
CSS 프로퍼티에는 키워드, 크기 단위, 색상 표현 단위 등의 특정 단위를 갖는 값을 지정한다. CSS에서 사용하는 대표적인 크기 단위는 px, em, %이다. px은 픽셀(화소) 단위이다. 1px은 화소 1개 크기를 의미한다. 픽셀은 디바이스 해상도(resolution)에 따라 상대적인 크기를 갖는다. %는 백분률 단위의 상대 단위이다. 요소에 지정된 사이즈(상속된 사이즈나 디폴트 사이즈)에 상대적인 사이즈를 설정한다. em은 배수 단위로 상대 단위이다. 요소에 지정된 사이즈에 상대적인 사이즈를 설정한다. rem은 최상위 요소(html)의 사이즈를 기준으로 삼는다. Viewport 단위는 상대적인 단위로 viewport를 기준으로 한 상대적 사이즈를 의미한다.

4)
 모든 HTML 요소는 Box 형태의 영역을 가지고 있다. Box는 콘텐트(Content), 패딩(Padding), 테두리(Border), 마진(Margin)로 구성된다. 브라우저는 박스 모델의 크기와 프로퍼티, 위치를 근거로 하여 렌더링을 실행한다. content는 요소의 텍스트나 이미지 등의 실제 내용이 위치하는 영역이다. Padding은 테두리(Border) 안쪽에 위치하는 요소의 내부 여백 영역이다. Border은 테두리 영역으로 border 프로퍼티 값은 테두리의 두께를 의미한다. Margin은 테두리(Border) 바깥에 위치하는 요소의 외부 여백 영역이다. margin 프로퍼티 값은 마진 영역의 두께를 의미한다.
 width와 height 프로퍼티는 요소의 너비와 높이를 지정하기 위해 사용된다. 기본적으로 width와 height 프로퍼티는 콘텐츠 영역을 대상으로 요소의 너비와 높이를 지정한다. 명시적으로 width와 height를 지정하기 위해서는 px, % 등의 크기 단위를 사용한다. margin / padding 프로퍼티는 content의 4개 방향(top, right, left, bottom)에 대하여 지정이 가능하다.
 border-style 프로퍼티는 테두리 선의 스타일을 지정한다. 프로퍼티 값의 갯수에 따라 4개 방향(top, right, left, bottom)에 대하여 지정이 가능하다. border-width 프로퍼티는 테두리의 두께를 지정한다. 프로퍼티 값의 갯수에 따라 4개 방향(top, right, left, bottom)에 대하여 지정이 가능하다. border-color 프로퍼티는 테두리의 색상을 지정한다. 프로퍼티 값의 갯수에 따라 4개 방향(top, right, left, bottom)에 대하여 지정이 가능하다. border-radius 프로퍼티는 테두리 모서리를 둥글게 표현하도록 지정한다. 프로퍼티 값은 길이를 나타내는 단위(px, em 등)와 %를 사용한다. border 프로퍼티는 border-width, border-style, border-color를 한번에 설정하기 위한 shorthand 프로퍼티이다. box-sizing 프로퍼티는 width, height 프로퍼티의 대상 영역을 변경할 수 있다.

5)
 font-size 프로퍼티는 텍스트의 크기를 정의한다. font-family 프로퍼티는 폰트를 지정한다. 컴퓨터에 해당 폰트가 설치되어 있지 않으면 적용되지 않는다. font-style 프로퍼티는 이탤릭체의 지정, font-weight 프로퍼티는 폰트 굵기 지정에 사용된다. line-height 프로퍼티는 텍스트의 높이를 지정한다. letter-spacing 프로퍼티는 글자 사이의 간격을 지정한다. text-align 프로퍼티는 텍스트의 수평 정렬을 정의한다. text-decoration 프로퍼티를 사용하여 링크 underline을 제거할 수 있다. 또는 텍스트에 underline, overline, line-through를 추가할 수도 있다. white space는 공백(space), 들여쓰기(tab), 줄바꿈(line break)을 의미한다. text-overflow 프로퍼티는 부모 영역을 벗어난 wrapping(자동줄바꿈)이 되지 않은 텍스트의 처리 방법을 정의한다. word-wrap 프로퍼티는 한 단어의 길이가 길어서 부모 영역을 벗어난 텍스트의 처리 방법을 정의한다. word-break 프로퍼티는 한 단어의 길이가 길어서 부모 영역을 벗어난 텍스트의 처리 방법을 정의한다.
6)
 position 프로퍼티는 요소의 위치를 정의한다. top, bottom, left, right 프로퍼티와 함께 사용하여 위치를 지정한다. static은 position 프로퍼티의 기본값으로 position 프로퍼티를 지정하지 않았을 때와 같다. 기본적인 요소의 배치 순서에 따라 위에서 아래로, 왼쪽에서 오른쪽으로 순서에 따라 배치되며 부모 요소 내에 자식 요소로서 존재할 때는 부모 요소의 위치를 기준으로 배치된다. relative (상대위치)는 기본 위치(static으로 지정되었을 때의 위치)를 기준으로 좌표 프로퍼티(top, bottom, left, right)를 사용하여 위치를 이동시킨다. absolute (절대위치)는 부모 요소 또는 가장 가까이 있는 조상 요소(static 제외)를 기준으로 좌표 프로퍼티(top, bottom, left, right)만큼 이동한다. fixed (고정위치)는 부모 요소와 관계없이 브라우저의 viewport를 기준으로 좌표프로퍼티(top, bottom, left, right)을 사용하여 위치를 이동시킨다. 스크롤이 되더라도 화면에서 사라지지 않고 항상 같은 곳에 위치한다. z-index 프로퍼티에 큰 숫자값을 지정할수록 화면 전면에 출력된다. positon 프로퍼티가 static 이외인 요소에만 적용된다. overflow 프로퍼티는 자식 요소가 부모 요소의 영역를 벗어났을 때 처리 방법을 정의한다.

7)
 float 프로퍼티는 주로 레이아웃을 구성할 때 블록 레벨 요소를 가로 정렬하기 위해 사용되는 중요한 기법이다. float 프로퍼티는 해당 요소를 다음 요소 위에 떠 있게(부유하게) 한다. float 프로퍼티를 사용하지 않은 블록 요소들은 수직으로 정렬된다. float:left; 프로퍼티를 사용하면 왼쪽부터 가로 정렬되고, float:right; 프로퍼티를 사용하면 오른쪽부터 가로 정렬된다. width 프로퍼티의 기본값은 100%이므로 width 프로퍼티값을 지정하지 않은 block 요소는 부모 요소의 가로폭을 가득 채운다. overflow: hidden 프로퍼티는 자식 요소가 부모 요소의 영역보다 클 경우 넘치는 부분을 안보이게 해주는 역할을 한다.
