<!DOCTYPE html>
<html>

<head>
    
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="Cat and Bulb.css"/>
</head>

<body>
    <div class="dark-background text-center">
        <div>
            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-dynamic-webapps/bulb-go-on-img.png" class="bulb-image" id="bulbImage" />
        </div>
        <div>
            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-dynamic-webapps/cat-img.png" class="cat-image" id="catImage" />
        </div>
        <div class="d-flex flex-row justify-content-center pt-5">
            <div class="switch-board">
                <h1 class="switch-status" id="switchStatus">Switched On</h1>
                <button class="off-switch" id="offSwitch" onclick="switchOff()">
                    OFF
                </button>
                <button class="on-switch" id="onSwitch" onclick="switchOn()">
                    ON
                </button>
            </div>
        </div>
    </div>
    <script src="Cat and Bulb.js"></script>
</body>

</html>
