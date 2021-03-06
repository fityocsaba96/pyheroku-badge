# pyheroku-badge
The simplest way to include a Heroku badge in your README file.  

> The idea was blatantly stolen from the [heroku-badge](https://github.com/pussinboots/heroku-badge) project.

![Heroku](https://pyheroku-badge.herokuapp.com/?app=pyheroku-badge)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Usage
Markdown:
```markdown
![Heroku](https://pyheroku-badge.herokuapp.com/?app=<HEROKU_APP_NAME>&style=<STYLE>)
```
reStructuredText:
```rst
.. image:: https://pyheroku-badge.herokuapp.com/?app=<HEROKU_APP_NAME>&style=<STYLE>
   :target: https://<HEROKU_APP_NAME>.herokuapp.com
   :alt: Heroku
```
Textile:
```textile
!https://pyheroku-badge.herokuapp.com/?app=<HEROKU_APP_NAME>&style=<STYLE>!:https://<HEROKU_APP_NAME>.herokuapp.com
```
## Available Styles
| `flat` (Default) | `flat-square` | `plastic` |
| --- | --- | --- |
| ![Heroku](https://github.com/DenisOH/pyheroku-badge/blob/master/img/deployed.svg) | ![Heroku](https://github.com/DenisOH/pyheroku-badge/blob/master/img/deployed-flat-square.svg) | ![Heroku](https://github.com/DenisOH/pyheroku-badge/blob/master/img/deployed-plastic.svg) |
| ![Heroku](https://github.com/DenisOH/pyheroku-badge/blob/master/img/failed.svg) | ![Heroku](https://github.com/DenisOH/pyheroku-badge/blob/master/img/failed-flat-square.svg) | ![Heroku](https://github.com/DenisOH/pyheroku-badge/blob/master/img/failed-plastic.svg) |
| ![Heroku](https://github.com/DenisOH/pyheroku-badge/blob/master/img/not-found.svg) | ![Heroku](https://github.com/DenisOH/pyheroku-badge/blob/master/img/not-found-flat-square.svg) | ![Heroku](https://github.com/DenisOH/pyheroku-badge/blob/master/img/not-found-plastic.svg) |

## License
```
WWWWWW||WWWWWW
 W W W||W W W
      ||
    ( OO )__________
     /  |           \
    /o o|    MIT     \
    \___/||_||__||_|| *
         || ||  || ||
        _||_|| _||_||
       (__|__|(__|__|
```
Code and documentation are available according to the MIT License (see [LICENSE](LICENSE)).

