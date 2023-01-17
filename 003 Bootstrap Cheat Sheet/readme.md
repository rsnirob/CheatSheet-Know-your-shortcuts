### Available breakpoints

|     Breakpoint    | Class infix | Dimensions |
|:-----------------:|:-----------:|:----------:|
|    Extra small    |     None    |   <576px   |
|       Small       |      sm     |   ≥576px   |
|       Medium      |      md     |   ≥768px   |
|       Large       |      lg     |   ≥992px   |
|    Extra large    |      xl     |   ≥1200px  |
| Extra extra large |     xxl     |   ≥1400px  |

### Containers

|                  | Extra small <576px | Small ≥576px | Medium ≥768px | Large ≥992px | X-Large ≥1200px | XX-Large ≥1400px |
|:----------------:|:------------------:|:------------:|:-------------:|:------------:|:---------------:|:----------------:|
|    .container    |        100%        |     540px    |     720px     |     960px    |      1140px     |      1320px      |
|   .container-sm  |        100%        |     540px    |     720px     |     960px    |      1140px     |      1320px      |
|   .container-md  |        100%        |     100%     |     720px     |     960px    |      1140px     |      1320px      |
|   .container-lg  |        100%        |     100%     |      100%     |     960px    |      1140px     |      1320px      |
|   .container-xl  |        100%        |     100%     |      100%     |     100%     |      1140px     |      1320px      |
|  .container-xxl  |        100%        |     100%     |      100%     |     100%     |       100%      |      1320px      |
| .container-fluid |        100%        |     100%     |      100%     |     100%     |       100%      |       100%       |

###### Default container


    <div class="container">
      <!-- Content here -->
    </div>
###### Responsive containers


    <div class="container-sm">100% wide until small breakpoint</div>
    <div class="container-md">100% wide until medium breakpoint</div>
    <div class="container-lg">100% wide until large breakpoint</div>
    <div class="container-xl">100% wide until extra large breakpoint</div>
    <div class="container-xxl">100% wide until extra extra large breakpoint</div>
###### Fluid containers

    <div class="container-fluid">
      ...
    </div>
