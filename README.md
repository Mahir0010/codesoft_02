# codesoft_02
<div class="wrapper">
  <div class="align">
  
  <!------ To-Do List App ----->
  <div class="app">
    <div class="info">
      <div class="date">
        <p id="day"><span id="today">Sunday,</span><span id="daymonth"> 30th</span></p>
        <p id='month'>January</p>
      </div>
      <div class="info-bottom">
        <div class="left">
          <p id="count">7</p>
          <p id="tasks">Total</p>
        </div>
        <div class="middle">
          <p id="remaining_done">5</p>
          <p id="remaining_tasks">Remaining</p>
        </div>
        <div class="right">
          <p id="count_done">2</p>
          <p id="tasks_done">Done</p>
        </div>
      </div>
    </div>
    
    <ul>
      <p id="today2"><strong>Tasks</strong> for today</p>
      <li class="lihiden">
        <a href="" class="check_button" onmousedown="return false">
          <i class="fa fa-check-circle mark" aria-hidden="true"></i>
        </a>
        <div class="right">
          <p contenteditable="true">Buy milk</p>
        </div>
        <span class="delete_button" onmousedown='return false'>
          <i class="fa fa-times-circle" aria-hidden="true"></i>
        </span>
      </li>
      
      <li class="lihiden">
        <a href="" class="check_button" onmousedown="return false">
          <i class="fa fa-circle-thin" aria-hidden="true"></i>
        </a>
        <div class="right">
          <p contenteditable="true">Buy bread</p>
        </div>
        <span class="delete_button" onmousedown='return false'>
         <i class="fa fa-times-circle" aria-hidden="true"></i>
        </span>
      </li>
      
      <li class="lihiden">
        <a href="" class="check_button" onmousedown="return false">
          <i class="fa fa-circle-thin" aria-hidden="true"></i>
        </a>
        <div class="right">
          <p contenteditable="true">Pay the bills</p>
        </div>
        <span class="delete_button" onmousedown='return false'>
         <i class="fa fa-times-circle" aria-hidden="true"></i>
        </span>
      </li>
      
      <li class="lihiden">
        <a href="" class="check_button" onmousedown="return false">
          <i class="fa fa-check-circle mark" aria-hidden="true"></i>
        </a>
        <div class="right">
          <p contenteditable="true">Go to barber shop</p>
        </div>
        <span class="delete_button" onmousedown='return false'>
         <i class="fa fa-times-circle" aria-hidden="true"></i>
        </span>
      </li>
      
      <li class="lihiden">
        <a href="" class="check_button" onmousedown="return false">
          <i class="fa fa-circle-thin" aria-hidden="true"></i>
        </a>
        <div class="right">
          <p contenteditable="true">Take a break</p>
        </div>
        <span class="delete_button" onmousedown='return false'>
         <i class="fa fa-times-circle" aria-hidden="true"></i>
        </span> 
      </li>
      
      <li class="lihiden">
        <a href="" class="check_button" onmousedown="return false">
          <i class="fa fa-circle-thin" aria-hidden="true"></i>
        </a>
        <div class="right">
          <p contenteditable="true">Conquer the World</p>
        </div>
        <span class="delete_button" onmousedown='return false'>
         <i class="fa fa-times-circle" aria-hidden="true"></i>
        </span>
      </li>
      
      <li class="lihiden">
        <a href="" class="check_button" onmousedown="return false">
          <i class="fa fa-circle-thin" aria-hidden="true"></i>
        </a>
        <div class="right">
          <p contenteditable="true">Conquer the Galaxy</p>
        </div>
        <span class="delete_button" onmousedown='return false'>
         <i class="fa fa-times-circle" aria-hidden="true"></i>
        </span>
      </li>
      
    </ul>
    
    <div class="bottom">
      <a href="" id="add-new" onmousedown="return false">
        <i class="fa fa-plus" aria-hidden="true"></i>
        Add new item
      </a>
    </div>
    
  </div>
    <p id="copyright">Made by&nbsp;<strong><a href="https://www.linkedin.com/in/nicolae-stefan-tudoran-b02291127/" target="_blank">Stefan Tudoran</a></strong></p>
  <!----- End To-Do List ------->
    
  </div>
</div>* {
  margin: 0;
  padding: 0;
}

body {
  background: #d2e3ed;
}
.wrapper {
  width: 100%;
  min-height: 960px;
   
  .align{
    width:100%;height:100%;
    margin: 0 auto;
    padding:80px 0;
  }

  /* To-Do List App */
  .app {
    width: 375px;
    min-height: 200px;
    margin: 0 auto;

    border-radius: 22px;
    background: #fff;
    text-shadow: 0 0 1px rgba(0, 0, 0, 0.1);
    letter-spacing: -1px;
    
    box-shadow: 0 5px 20px rgba(0, 0, 0, 0.15);
    
    -webkit-backface-visibility: hidden;
    
    -webkit-user-select: none;
    -moz-user-select: none;
    user-select: none;

    .info {
      position: relative;
      height: 170px;
      width: auto;

      border-top-left-radius: 22px;
      border-top-right-radius: 22px;
      //linear-gradient(135deg, rgba(15,184,173,.75) -10%, rgba(44,181,232,.75) 130%)
      background: linear-gradient(135deg,rgba(158, 15, 184, 0.70) -10%,rgba(5, 232, 255, 0.8) 180%),
        url('https://static.vecteezy.com/system/resources/previews/000/101/253/non_2x/vector-free-abstract-background-1.jpg');
      background-size: cover;

      .date {
        position: relative;
        width: 100%;
        padding: 11px 0 5px 0;

        #day, #month {
          text-align: center;
          font-size: 26px;
          color: #fff;
        }
        #month {
          font-size: 16px;
        }
        #today {
          font-weight: bold;
        }
      }
      .info-bottom {
        position: relative;
        height: 50px; width: 85%;
        margin: 40px auto 0 auto;
        text-shadow: 0 0 1px rgba(0,0,0,0.2);
        .left {
          float: left;
        }
        .right {
          float: right;
        }
        .middle {
          position: absolute;
          width: 140px;
          margin: 0 auto;
          left: 0; right: 0;
        }

        #count,
        #tasks,
        #count_done,
        #tasks_done,
        #remaining_done,
        #remaining_tasks {
          margin-top: 11px;
          font-size: 19px;
          color: #fff;
          font-weight: bold;
          text-align: center;
        }
        #tasks, #tasks_done, #remaining_tasks {
          font-weight: normal;
          font-size: 18px;
          margin-top: -2px;
        }
      }
    }

    ul {
      height: 100%;
      margin: 10px auto 10px auto;

      #today2 {
        width: 100%; height: 52px;
        margin: 10px auto;
        
        font-size:18px;
        text-align: center;
        color: #636363;
        line-height: 52px;
      }

      li {
        position: relative;
        display: flex;
        list-style: none;
        margin: 10px auto;
        width: 92%; min-height: 37px; line-height:37px;

        color: #636363;
        
        -webkit-transition: all ease-in-out 0.35s;
        -moz-transition: all ease-in-out 0.35s;
        -o-transition: all ease-in-out 0.35s;
        transition: all ease-in-out 0.35s;
        
        &.lihiden{
          opacity:0;
        }
        a {
          width: 35px; height: 30px;
          display: inline-block;
          color: #636363;
          text-decoration: none;
          i {
            position: absolute;
            top: 6px; left: 7px;
            -webkit-transition: all ease-in-out 0.5s;
            -moz-transition: all ease-in-out 0.5s;
            -o-transition: all ease-in-out 0.5s;
            transition: all ease-in-out 0.5s;
            
            font-size: 20px;
            font-weight: bold;
          }
          .mark {
            color: #744bc0;
          }
          .mark-alt {
            color: #636363;
          }
        }
        a:hover > i {
          color: #744bc0;
        }

        .right {
          width: 80%;
          height: 100%;
          display: inline-block;
          margin: -3px auto 0 auto;

          p {
            display: inline-block;
            width: 90%; height: 28px;
            word-wrap: break-word;
            
            line-height: 28px;
            outline: none;
            margin: 0;

            font-size: 15px;
            letter-spacing: -1px;
            font-weight: bold;

            -webkit-transition: all ease-in-out 0.25s;
            -moz-transition: all ease-in-out 0.25s;
            -o-transition: all ease-in-out 0.25s;
            transition: all ease-in-out 0.25s;

            span {
              cursor: text;
            }
          }
          .line-through {
            color: #b3b3b3;
            text-decoration: line-through;
            font-style: italic;
            transform:translateX(7px;)
          }
        }

        span {
          display: inline-block;
          position:relative;
          width: 35px; height: 30px;
          cursor: pointer;
          
           -webkit-transition: all ease-in-out 0.35s;
          -moz-transition: all ease-in-out 0.35s;
          -o-transition: all ease-in-out 0.35s;
          transition: all ease-in-out 0.35s;
          i {            
            font-size: 20px;
            transform:translate(9px,-1px);
          }
        }
        span:hover > i {
          color: rgba(36, 181, 226, 1);
        }
      }
    }

    .bottom {
      height: 80px;
      width: auto;
      margin-top: -300px;
      
      -webkit-transition: all ease-in-out 0.40s;
      transition: all ease-in-out 0.40s;
      
      &.show{
        margin-top: -24px;
      }

      a {
        display: block;
        width: 150px; height: 40px; line-height: 40px;
        margin: 40px auto 0 auto;
        padding: 0 10px;
        font-size: 18px;
        background: linear-gradient( 135deg,rgba(158, 15, 184, 0.9) -20%,rgba(5, 232, 255, 0.9) 165%);
        color: #fff;
        border-radius: 20px;
        text-decoration: none;
        text-align: center;

        i {
          margin-right: 5px;
        }
      }
      a:hover {
        background: linear-gradient(135deg,rgba(158, 15, 184, 0.8) -20%,rgba(5, 232, 255, 0.8) 165%);
      }
      a:active{
        transform:translateY(1px);
        background: linear-gradient(135deg,rgba(158, 15, 184, 0.9) -20%,rgba(5, 232, 255, 0.9) 165%);
      }

      #undo {
        width: 30px; height: 30px;
        
        border-radius: 100px;
        float: right;
        line-height: 30px;
        opacity: 0;
        cursor: default;

        margin-top: -54px;
        margin-right: 21px;

        pointer-events: none;

        i {
          margin-left: 5px;
        }
      }
    }
  }
  /* End To-Do List App */
}

.down {
  -webkit-animation: slide_down .4s;
  -moz-animation: slide_down .4s;
  -o-animation: slide_down .4s;
  animation: slide_down .4s;
}
@keyframes slide_down {
  0% {
    opacity: 0;
    transform: scale(0);
    margin-top: -41px;
  }
  20% {
    opacity: 0;
  }
  80% {
    transform: scale(1.05);
  }
  100% {
    opacity: 1;
    transform: scale(1);
    margin-top: 10px;
  }
}

.up {
  -webkit-animation: slide_up .6s;
  -moz-animation: slide_up .6s;
  -o-animation: slide_up .6s;
  animation: slide_up .6s;
}
@keyframes slide_up {
  0% {
    opacity: 1;
    transform: scale(1);
    margin-top: 10px;
  }
  30% {
    opacity: 0;
  }
  100% {
    opacity: 0;
    transform: scale(0);
    margin-top: -45px;
  }
}

.down_in {
  -webkit-animation: down_in .35s;
  -moz-animation: down_in .35s;
  -o-animation: down_in .35s;
  animation: down_in .35s;
}
@keyframes down_in {
  0% {
    opacity: 0;
    transform: scale(.5) translateY(-55px);
  }
  70% {
    transform: scale(1.07);
  }
  100% {
    opacity: 1;
    transform: scale(1) translateY(0px);
  }
}
.pop_out {
  -webkit-animation: pop_out .25s;
  -moz-animation: pop_out .25s;
  -o-animation: pop_out .25s;
  animation: pop_out .25s;
}

.pop_in {
  -webkit-animation: pop_in .35s;
  -moz-animation: pop_in .35s;
  -o-animation: pop_in .35s;
  animation: pop_in .35s;
}
@keyframes pop_in {
  0% {
    opacity: 0;
    transform: scale(0);
  }
  70% {
    transform: scale(1.20);
  }
  100% {
    opacity: 1;
    transform: scale(1);
  }
}
#copyright {
  font-size: 15px;
  color: #8baec3;
  margin: 30px auto 0 auto;
  font-family: 'Noto Sans', sans-serif;
  text-shadow: 0 0 1px rgba(0, 0, 0, 0.05);
  width: 250px;
  text-align: center;
  a {
    text-decoration: none;
    color: #8baec3;
    -webkit-transition: all ease-in-out 0.35s;
    -moz-transition: all ease-in-out 0.35s;
    -o-transition: all ease-in-out 0.35s;
    transition: all ease-in-out 0.35s;
        letter-spacing: 0px;
  }
  a:hover {
    color: #fff;
  }
}
