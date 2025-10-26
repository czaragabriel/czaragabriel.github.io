---
title: testing admin panel
---

There some test goin on

```

export class car{
    constructor(brand){
        this.name = brand;
    }
    show(){
        console.log(`Car name: ${this.name}`);
    }
}
export class Model extends car{
        constructor (brand, model){
        super(brand); //no need to repeat this.name = brand
        this.model = model;
    }
    showw(){
        console.log(this.show() + this.model);
    }

}

```
