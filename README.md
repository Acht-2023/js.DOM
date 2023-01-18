1 кт
    <script>

        function Y1(arg1, yes, no) {
            if (arg1 < 12) yes(arg1)
            else no(arg1)
        }
        function callbackyes() {
            console.log(arg1 - 1);
        }
        function callbackno() {
            console.log(5 * arg1 - 2);
        }
        let arg1 = Number(prompt("Введи значение X"));
        Y1(arg1, callbackyes, callbackno);
    </script>
