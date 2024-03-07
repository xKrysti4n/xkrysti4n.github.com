 * Główny plik SCSS projektu. /scss/main.scss
  
   * Ten plik służy jako centralny węzeł importu wszystkich innych plików SCSS w projekcie.
   * Odpowiada za importowanie i organizowanie wszystkich stylów użytych w projekcie.
   * Kolejność importu ma znaczenie, ponieważ określa kaskadę w CSS.
   
   * @import "abstracts/variables"; - Ten plik zawiera wszystkie zmienne SCSS użyte w projekcie.
   * @import "abstracts/mixins"; - Ten plik zawiera wszystkie miksy SCSS, które są blokami kodu wielokrotnego użytku.
   * @import "abstracts/functions"; - Ten plik zawiera wszystkie funkcje SCSS użyte w projekcie.
   
   * @import "base/animations"; - Ten plik zawiera wszystkie klatki kluczowe i animacje użyte w projekcie.
   * @import "base/base"; - Ten plik zawiera podstawowe style projektu.
   * @import "base/typography"; - Ten plik zawiera wszystkie style typografii użyte w projekcie.
   * @import "base/utilities"; - Ten plik zawiera klasy narzędziowe, które są małymi klasami przeznaczonymi do jednego celu.

