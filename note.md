.container{
    /* height: 500px; */
    display: flex;
    /* flex-wrap: wrap; */
    /* flex-direction: column;
    justify-content:center;
    align-items: center; */
    background: rgb(204, 204, 204);
}

.item{
    flex-basis: 100px;
    height: 100px;
    background: #2542ef;
    margin: 10px;
    color: #fff;

    display: flex;
    justify-content: center;
    align-items: center;

}



.item:nth-of-type(1){
    order: 3;
}

.item:nth-of-type(2){
    order: 2;
}

.item:nth-of-type(3){
    order: 1;
    flex-basis: 300px;
} 