Here's the optimized code:

```
.Header01 {
    position: absolute;
    top: 20px;
    left: 108.68px;
    padding: 10px;
    font: 500 18px/22px 'Kanit';
    letter-spacing: 0.04em;
    text-transform: capitalize;
    color: #000;
    flex: none;
    order: 1;
    flex-grow: 0;
}

.container {
    position: absolute;
    top: 22px;
    right: 99px;
    display: flex;
    flex-direction: row-reverse;
    padding: 10px;
}

.list-item, .list-item1 {
    display: flex;
    flex-direction: row-reverse;
    align-items: center;
    padding: 10px;
    border-color: transparent;
    font: 500 14px/18px 'Inter';
    color: #081E34;
}

.list-item {
    justify-content: flex-end;
}

.list-item1 {
    justify-content: flex-end;
    margin-left: 20px;
    border-radius: 20px;
}
```