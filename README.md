# semantic-ui-range-minmax
Add-on range slider for Semantic UI forked from [https://github.com/tyleryasaka/semantic-ui-range]

With added functions for setting min and max values dynamically

Please refer to the original documentation for basic usage

## Setting min and max values programmatically

You can set min and max values without resetting the whole slider (which could make it briefly blink on the page)

    $('#range').range('set min', 0);
    $('#range').range('set max', 100);
