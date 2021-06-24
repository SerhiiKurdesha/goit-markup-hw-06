.accept::before{
    content: '';
    display: block;
    border-radius: 4px;
    width: 16px;
    height: 15px;
    border: 2px solid #000000;
}
.input-accept:checked + .accept::before{
    background-color: #2196f3;
}
.checkbox{
    -webkit-appearance: none;  
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    border: 0;
    padding: 0;
    clip: rect(0 0 0 0);
    overflow: hidden; 
} 
.checkbox-accept{
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 20px;
    margin-bottom: 30px;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 1.71;
    letter-spacing: 0.03em;
    color: var(--primary-text-color);
    cursor: pointer;
} 
.checkbox-bord{
    display: inline-block;
    margin-right: 9px;
    width: 16px;
    height: 15px;
    border: 2px solid var(--title-text-color);
    border-radius: 4px;
}  
.checkbox:checked + .checkbox-bord{
    border-color: transparent;
    background-color: var(--accent-color); 
    background-image: url('../images/new-post/sprite2.svg#icon-bord-white');
    background-origin: border-box;
    background-size: contain;
} 