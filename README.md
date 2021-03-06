## Caroll
#### Admin Template

Caroll is a simple and light admin template.
Main part of this template is using only HTML and CSS

JS used for datetime picker & datatable:
1. [DataTable - JQuery plugin](https://datatables.net) (170611 - removed from source)
2. [Datetimepicker](https://jqueryui.com/datepicker)

![mss]

![dss]

[mss]: https://raw.githubusercontent.com/irwanphan/caroll/7f348ed5902464233e6b76092429e3073a3f8125/assets/images/caroll00.PNG "mobile screenshot"
[dss]: https://github.com/irwanphan/caroll/blob/fef8d3aadf0083fa5948dd08168603bd4d85759a/assets/images/caroll.PNG?raw=true "desktop screenshot"

### Grid

The grid system is using [tatami.css](https://github.com/irwanphan/tatami) for simple usage.
You can find and edit the __sass__ source files within the _assets folder_
The usage is really simple, e.g:

| class      | def.                 |
| ---------- |:--------------------:|
| col-2      | two columns width    |
| col-3      | three columns width  |
| col-12     | twelve columns width |

_note: it's been a long time since first creation on tatami and has not been updated since then, the grid system was for learning purpose, but hopefully can be used for quick gridding._
_tatami container width and number of columns can be adjusted at **tatami-base.sass**._

Other than the __tatami__, __grid-foundation.css__ is also available within the assets/css source folder, so if you are familiar with [Zurb Foundation](foundation.zurb.com), you may switch the link css to grid-foundation.css which is really recommended.

### Button

You can add button style by adding two classes, e.g __.button .blue__ __.button .orange__ or __.button .theme__ which is the theme color and or theme sub.
The color setting may be changed within the __main.sass__ file.
