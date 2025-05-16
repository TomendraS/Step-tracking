# My daily walking summury

## step i walked
<!--Table-->
| Name | Age | Genger |
|------|-----|--------|
| Tom  | 35  |  M     |
| Rex  | 32  |  M     |
| Ami  | 27  |  F     |
| SAdi | 28  |  F     |

### Tod do list
- [ ] Monday
- [x] Tuesday
- [ ] Wedenesday
- [x] Thursday

```scheme
(define steps '(8542 6781 9234 7890 10456 12345 5678))

(define (average lst)
  (/ (apply + lst) (length lst)))

(display "Average steps per day: ")
(display (average steps)) ; => 8703
```