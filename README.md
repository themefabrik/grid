# Grid

grid.css is a simple and lightweight grid based system for multi column HTML layouts. It is based on 12 columns, allows nested grids, is responsive, easy to customize and suits the needs to kickstart smaller and minimalistic web projects.

## Installation

Simply include the grid.css resource inside the <head> section of your HTML page.

```
<link rel="stylesheet" type="text/css" href="css/grid.css" />
```

## Usage

Each grid section needs the .grid class wrapped around the columns. 

```
<div class="grid">
    <div class="col span-6">...</div>
    <div class="col span-6">...</div>
</div>
```
Nested grids need another .grid class wrapped inside the column. 
```
<div class="grid">
    <div class="col span-6">
        <div class="grid">
            <div class="col span-4">...</div>
            <div class="col span-8">...</div>
        </div>
    </div>
    <div class="col span-6">
        <div class="grid">
            <div class="col span-4">...</div>
            <div class="col span-8">...</div>
        </div>
    </div>
</div>
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Feel free to improve the concept of this 

Please make sure to update tests as appropriate.

## License
This project is licensed under the **MIT License**.