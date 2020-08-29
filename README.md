Active Code:


# jQuery-Timer-down
$("#getting-started")
.countdown("2021/07/11", function (event) {
    $('.days').text(
        event.strftime('%D')
    );
    $('.hours').text(
            event.strftime('%H')
        );
    $('.minuit').text(
            event.strftime('%M')
        );
    $('.seconds').text(
            event.strftime('%S ')
        );
});
