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