# Ex-06-Book-Cover-Design
## AIM:
To develope a website to display the cover page design of a book.

## Design Steps:

### Step 1:
Clone the GitHub repository and create a Django admin interface.

### Step 2:
Write HTML and CSS Code for desiging book cover page and excute them.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(255, 255, 255);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/backcover.jpeg);
            background-size: cover;
    }
        

    .insight{
        color: brown;

    }

    
    .hrstyle{
        width:100px;
    }
    .author{
    
        display: inline;
        position: relative;
        color: red;
        top:190px;
        
        font-family:Georgia;
        font-size: medium;
    }
    .booktitle{
        font-family: 'Courier New', Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        top: 30px;
    
    }
    .id {
        width:400px;
        position: relative;
        top:180px;
        
    }
    .pub{
        font-size: medium;
        position: relative;
        top:155px;
        left:330px;
    }
    .ed{
        color: black;
        font-size: medium;
        font-family: Verdana;
        position:relative;
        top:85px;

    }
    .subtitle{
        font-family:Tahoma;
        font-size: large;
        position: relative;
        top:40px;
    }
    .mypic{
        position: relative;
        top: 135px;
        left: 260px;
        width: 100px;
        height: 100px;
        background-size: cover;
    }
    </style>
    <title>Book Cover Page</title>
</head>
<body>
    <div class="bookpage">
        <div class="insight">
            SEC INSIGHT
        </div>
        <div class="hrstyle">
            <hr style="color: red(253, 238, 238);">
        </div>
        <div class="booktitle">
            <h1>Fundamentals of Web Application Development</h1></div>
        <div class="subtitle">
            HTML and CSS Combined with Django Architecture
        </div>
        <div class="mypic">
            <img src="/static/images/abhi.jpeg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: orange;">
        </div>
        <div class="author">
           <p><b>Abishek</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>Second Edition</b>
        </div>
    </div>
</body>
```

## Output:

![Screenshot_20230128_090436](https://user-images.githubusercontent.com/119405626/215275382-b4ba7295-5d08-411f-9234-4cdda12983cf.png)


## HTML Validator

![Screenshot_20230128_090508](https://user-images.githubusercontent.com/119405626/215275390-b84ddc78-0e71-41f2-a33a-3245155bdc6a.png)


## Result:
The program for designing book cover page using HTML and CSS is executed successfully.
