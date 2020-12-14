 var photos = ["https://i.pinimg.com/originals/0d/b9/06/0db906107ce0e53854b44fd1734091fa.jpg","https://images.unsplash.com/photo-1543862475-eb136770ae9b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&w=1000&q=80","https://64.media.tumblr.com/9629e0d2a3620a048ff03783aa0ac03a/tumblr_owtlvo52jv1wcvklao1_400.jpg"
    ];

console.log(photos);

photos.forEach(function(item,photo){
    $(".show").append("<img src=" + photos[photo] + ">");
                
});

$("button").click(function(){
    var links=$(".inputName").val();
        
    photos.push(links);
    
    $(".inputName").val("");
     
    $('.show').empty();
    
    photos.forEach(function(item,photo){
        
    $(".show").append("<img src=" + photos[photo] + ">");
            
});

});

