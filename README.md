.body{background:#59ABE3;margin:0}
.form{width:340px;height:440px;background:#e6e6e6;border-radius:8px;box-shadow:0 0 40px -10px #000;margin:calc(50vh - 220px) auto;padding:20px 30px;max-width:calc(100vw - 40px);box-sizing:border-box;font-family:'Montserrat',sans-serif;position:relative}
.h2{margin:10px 0;padding-bottom:10px;width:180px;color:#78788c;border-bottom:3px solid #78788c}
.input{width:100%;padding:10px;box-sizing:border-box;background:none;outline:none;resize:none;border:0;font-family:'Montserrat',sans-serif;transition:all .3s;border-bottom:2px solid #bebed2}
.input:focus{border-bottom:2px solid #78788c}
.button{float:right;padding:8px 12px;margin:8px 0 0;font-family:'Montserrat',sans-serif;border:2px solid green;background:0;color:green;cursor:pointer;transition:all .3s}
.button:hover{background:green;color:green}
.div{content:'Hi';position:absolute;bottom:-15px;right:-20px;background:#50505a;color:#fff;width:320px;padding:16px 4px 16px 0;border-radius:6px;font-size:13px;box-shadow:10px 10px 40px -14px #000}
.span{margin:0 5px 0 15px}
.cav-item{
	color:#fff;
	text-decoration: none;
	margin-right: 25px;
	 font-size:16px;
	 margin:0px 100px;
}
.body {
        --primary: 25,91,255;
        --color: 44, 62, 80;
        --bg: 255, 255, 255;
        --red: 255, 0, 78;
        height: 100vh;
        background: #f2f6f9;
        height: calc(var(--vh, 1vh) * 100);
        overflow: auto;
        color: rgb(var(--color));
        width: 100%;
    }
    * {
        list-style: none;
        outline: none;
        padding: 0;
        margin: 0;
        font-family: 'Open Sans', sans-serif;
        box-sizing: border-box;
    }
    .b {
        padding: 0px 4px;
        display: inline-block;
    }
    .con-items {
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
    }
    .item {
        width: 360px;
        background: #fff;
        box-shadow: 0px 5px 30px 0px rgba(0,0,0,.05);
        border-radius: 40px;
        margin: 0px;
        padding: 30px;
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        transition: all .25s ease;
        position: relative;
    }
    .item:not(.color):hover{
        transform: scale(1.05);
    }
    .item:hover .con-img{
        transform: scale(1.15);
    }
    .item.color:hover {
        transform: scale(1.15);
    }
    .con-img {
        display: flex;
        align-items: center;
        justify-content: center;
        transition: all .25s ease;
    }
    .con-img img {
        width: 130px;
    }
    .item1 {
        padding-right: 45px;
    }
    .item2 {
        z-index: 100;
    }
    .item3 {
        padding-left: 45px;
    }
    .item.color {
        background: #3dcbab;
        color: #fff;
        transform: scale(1.1);
    }
    .item.color li {
        color: rgba(255,255,255,.75);
    }
    .item.color li b {
        color: rgba(255,255,255,1);
    }
    .item.color li i {
        color: rgba(255,255,255,1);
    }
    .item header {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        position: relative;
        width: 100%;
    }
    .item header h3 {
        font-size: 2rem;
    }
    .item header p {
        font-size: 1.2rem;
    }
    .badge {
        position: absolute;
        top: 20px;
        right: 20px;
        background: #191970;
        padding: 5px 10px;
        border-radius: 12px;
        color: rgb(61, 203, 171);
        font-weight: bold;
        font-size: .85rem;
    }
    .item ul {
        padding: 20px 0px;
        flex: 1;
        width: 100%;
    }
    .item ul li {
        width: 100%;
        padding: 10px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
        text-align: left;
        color: rgb(var(--color), .5)
    }
    .item ul li b {
        color: rgb(var(--color), 1)
    }
    .item ul li i {
        font-size: 1.6rem;
        margin-right: 15px;
        color: rgb(var(--color), 1)
    }
    .item button {
        padding: 14px 20px;
        width: 100%;
        background: rgb(61, 203, 171);
        border: 3px solid transparent;
        border-radius: 20px;
        color: #fff;
        font-weight: bold;
        font-size: 1.1rem;
        box-shadow: 0px 10px 25px 0px rgba(61, 203, 171, .35);
        cursor: pointer;
        transition: all .25s ease;
    }
    .item button:not(.border):hover {
        transform: translate(0,5px);
        box-shadow: 0px 0px 0px 0px rgba(61, 203, 171, .35);
    }
    .item button.border {
        border: 3px solid #fff;
    }
    .item button.border:hover {
        background: #fff;
        color: rgb(61, 203, 171);
    }
