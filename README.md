# Session1

1. basics of html 5
2. css 3.
3. undestanding html-server.
4. upload the code on gitlab.

## html5

1. create a basic html page this h1 tags.

## server

1. in order to deploy your html page you required a server.
2. server may be http-server or live-server.
3. you need to install the servers. To install
    - http-server :- "npm install -g http-server"
    - live-server :- "npm install -g live-server"
4. http-server vs live-server
    - http-server
        - static in nature.
    - live-server
        - dynamic server.
5. In order to run 
    - http-server:- http-server
    - live-server :- live-server
6. hit the browser with cmd localhost:8080.

## html
1. Semantic Elements in html5:-
    - introduced in html 5
    - has its own meaning but no style attached.
    - good for bots to read your document.
    - they are
        - header
        - footer
        - main
        - section
        - artical
        - nav

## css

1. used to style your page.
2. 3 ways to use it
    - inline
        - css in the line of the html tag
        - using style attribute of html tag.
        - Example <h1 style="background-color:red">
        - usage:-
            - used whenthe change is just for that tag only

    - internal
        - css created inside your html page.
        - css is written inside style tag.
        - need selectors to load.
        - example  <style>
                    h1{
                        background-color: red;
                    }
                    </style>
        - usage:-
            - helps when the change is for a specific page.
            - make code very long.
            - bit faster the external.

    - external
        - css outside your html page.
        - need selectors to load.
        - need link tag to load the css.
        - usage
            - it is most reusable.
            - easy to use.
            - less mantanance
            - keep both html and css seprate as easy to update.
            - make both more readable.
3. margin :-
    - Space between two html elements.
    - no effect in tag size.
4. padding:-
    - Space inside your tag.
    - will effect the tag size
5. units
    - px
        - static
        - always fixed for each and every device. 
    - em
        - dynamic
        - 1em = font size(16px)
    - %
        - full width of the page.
6. 2 type of elements:-
    - block 
        - covers the full width of the page
        - change the look by using display attribute.
    - inline 
        - covers the min area.
        - change the look by using display attribute.
7. Selectors:-
    - helps to read html doc so that css can be aplyed on it.
    - 3 types
        - tag name
            - can be used directly with the name
            - will be aplied on all the tags of same type
        - class name
            - need to use (.) befor the class-name
            - will be aplied to a group of tags on which same class is specified. 
        - id
            - need to use (#) before the id name
            - will be unique for every tag.

