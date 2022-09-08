* Denis Moiseev
*   + Telegram: [@adhdenis](https://t.me/adhdenis)
    + Discord: Randomshot#4136
* Learning coding both as necessary tool and way of creative expression. Intersted in making web more interactive and immersive. 
* Currently can write and read simple code in JavaScript, C, Go. Comfortable with adaptive styling using CSS and HTML. Also understand the importance of Git in collaborative work :)
* Code example: Go solution of Two Oldest Ages from Codewars


    package kata
    import "fmt"

    func TwoOldestAges(ages []int) [2]int {
    var arr [2]int
    for _, v := range ages {
    if v > arr[0] {
        arr[0] = v
        if v > arr[1]{ 
            arr[0] = arr[1]
            arr[1] = v
        }
        fmt.Println(arr)
    }
    }
    return arr
    }


* Projects: libft, odin-calculator, odin-etch-a-sketch
* Education: couple months in School 21 + self-learning
*   + Russian: Native
    + English: B2 (C1 if I'm lucky :')