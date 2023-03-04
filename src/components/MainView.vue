<template>
    <div class="leftContainer">
        <div id="cityNameBox">
            <div class="cityName">
                <p>San Fransisco</p>
                <p>Jan 28</p>
            </div>
        </div>
        <div id="contentsBox">
            <div class="buttonBox">
                <div class="buttonBackground">
                    <button class="forecast">Forecast</button>
                    <button class="airquality">Air Quality</button>
                </div>
            </div>
            <div class="weatherBox">
                <div class="weatherDegree">
                    <p>10&deg;</p>
                </div>
                <div class="weathericon">
                    <img src="" alt="Mainlogo" />
                </div>
                <div class="weatherData">
                    <div>
                        <p></p>
                        <p></p>
                    </div>
                </div>
            </div>
        </div>
        <div id="todayWeather">
            <div class="textBox">
                <p>시간대별 날씨 정보</p>
                <p>이번주 날씨 보기</p>
            </div>
        
            <div class="timelyWeatherBox">
                <div class="timelyWeather">
                    <div class="icon">
                        <img src="" alt="" />
                    </div>
                    <div class="data">
                        <p class="time">2pm</p>
                        <p class="currentDegree">32&deg;</p>
                        <div>
                            <img src="" alt="" />
                            <p class="fall">15%</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <nav>
            <i class=""></i>
            <i class=""></i>
            <i class=""></i>
            <i class=""></i>
        </nav>
    </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import '~@/scss/main.scss';

.leftContainer{
    width: 324px;
    height: 700px;
    border-radius: 50px;
    background: linear-gradient(#16455f, #0e1239);
    box-shadow: 5px 5px 10px gray;
}
</style>

