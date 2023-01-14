<div class="contenedor">
    <h1>Julián Castro;<span>&#160;</span></h1>
    <style>
        body { 
        font-family: monospace; 
        background: tomato;
    }
    .contenedor {
        margin: auto;
        display: table;
    }
    
    h1 { 
        position: relative; 
        float: left;
        background: tomato;
        color: #fff;
        font-size: 2.5em;
    }
    
    h1 span {
        position:absolute;
        right:0;
        width:0;
        background: tomato;
        border-left: 1px solid #000;
        animation: escribir 2s steps(40);
    }
    
    @keyframes escribir {
        from { width: 100% }
        to { width:0 }
    }
    </style>
</div>
