# I2Cdev-2020-02-25
This is a copy for [XOD](https://xod.io/) patches of **[Jeff Rowberg's I2Cdev Library - 2020-02-25](https://www.i2cdevlib.com/)**

How to use in a **XOD patch**:

````
#pragma XOD error_raise enable

#pragma XOD require "https://github.com/as000fm/I2Cdev-2020-02-25"

{{#global}}
#include <I2Cdev.h>
{{/global}}

struct State {
};

{{ GENERATED_CODE }}

void evaluate(Context ctx) {
    //auto inValue = getValue<input_IN>(ctx);
    //emitValue<output_OUT>(ctx, inValue);
}
````
