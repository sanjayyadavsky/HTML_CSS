# assignment no 4 

learning, after using float propert always clear it 
``` css
.clearfix{
    clear:both;
}
```
## her the way to how to do it 

### html
``` html
        <ul class="list">
              <li class="list-item">Home</li>
              <li class="list-item">About</li>
              <li class="list-item">Services</li>
              <li class="list-item">Portfolio</li>
              <li class="list-item">Pricing</li>
        </ul>
            <div class="clearfix"></div>
```
### css 
``` css
.clearfix{
    clear:both;
}
ul{
    overflow :hidden;
}
```
Always try to clearfix parent element **and** some time we have to use overflow property  

# given sample 
![alt text](./thumbnail.png)

# Result
![alt text](./assets/Screenshot%202022-12-21%20at%2011.59.12%20pm.png
)