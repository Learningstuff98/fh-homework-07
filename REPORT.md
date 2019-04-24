Inspecting 1 file
C

Offenses:

image_blur_2.rb:1:1: C: Layout/EndOfLine: Carriage return character detected.
class Image ...
^^^^^^^^^^^
image_blur_2.rb:1:1: C: Style/Documentation: Missing top-level class documentation comment.
class Image
^^^^^
image_blur_2.rb:2:1: C: Layout/EmptyLinesAroundClassBody: Extra empty line detected at class body beginning.
image_blur_2.rb:28:81: C: Metrics/LineLength: Line is too long. [92/80]
    @array[row + 1][col] = 1 if row + 1 <= @array.length - 1 && (@array[row + 1][col]).zero?
                                                                                ^^^^^^^^^^^^
image_blur_2.rb:32:81: C: Metrics/LineLength: Line is too long. [97/80]
    @array[row][col + 1] = 1 if col + 1 <= @array[row].length - 1 && (@array[row][col + 1]).zero?
                                                                                ^^^^^^^^^^^^^^^^^
image_blur_2.rb:47:1: C: Layout/EmptyLinesAroundClassBody: Extra empty line detected at class body end.
image_blur_2.rb:51:3: C: Layout/IndentArray: Use 2 spaces for indentation in an array, relative to the first position after the preceding left parenthesis.
  [0, 0, 1, 0],
  ^^^^^^^^^^^^
image_blur_2.rb:55:1: C: Layout/IndentArray: Indent the right bracket the same as the first position after the preceding left parenthesis.
])
^

1 file inspected, 8 offenses detected
