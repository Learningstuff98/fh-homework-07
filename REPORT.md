Inspecting 1 file
C

Offenses:

image_blur_2.rb:1:1: C: Layout/EndOfLine: Carriage return character detected.
class Image ...
^^^^^^^^^^^
image_blur_2.rb:1:1: C: Style/Documentation: Missing top-level class documentation comment.
class Image
^^^^^
image_blur_2.rb:23:5: C: Style/GuardClause: Use a guard clause instead of wrapping the code inside a conditional expression.
    if row - 1 >= 0 && (@array[row - 1][col]).zero?
    ^^
image_blur_2.rb:23:5: C: Style/IfUnlessModifier: Favor modifier if usage when having a single-line body. Another good alternative is the usage of control flow &&/||.
    if row - 1 >= 0 && (@array[row - 1][col]).zero?
    ^^
image_blur_2.rb:29:5: C: Style/GuardClause: Use a guard clause instead of wrapping the code inside a conditional expression.
    if row + 1 <= @array.length - 1 && (@array[row + 1][col]).zero?
    ^^
image_blur_2.rb:35:5: C: Style/GuardClause: Use a guard clause instead of wrapping the code inside a conditional expression.
    if col + 1 <= @array[row].length - 1 && (@array[row][col + 1]).zero?
    ^^
image_blur_2.rb:41:5: C: Style/GuardClause: Use a guard clause instead of wrapping the code inside a conditional expression.
    if col != 0 && (@array[row][col - 1]).zero?
    ^^
image_blur_2.rb:41:5: C: Style/IfUnlessModifier: Favor modifier if usage when having a single-line body. Another good alternative is the usage of control flow &&/||.
    if col != 0 && (@array[row][col - 1]).zero?
    ^^

1 file inspected, 8 offenses detected
