# Database Table: Cars for Sale

## Table Name

`cars_for_sale`

## Columns

id:                 (INT)           NOT_NULL    primary key     auto_increment
manufacturer:       VARCHAR(30)     NOT_NULL
model:              VARCHAR(70)     NOT_NULL
fuel_type:          VARCHAR(9)      NOT_NULL
transmission_type:  VARCHAR(11)     NOT_NULL
number_of_doors:    (TINYINT)       NOT_NULL
color:              VARCHAR(20)     NULL
production_year:    YEAR()          NOT_NULL
is_used:            (TINYINT)       NOT_NULL    DEFAULT(0)
kms:                (INT)           NULL
price:              DECIMAL(10,2)   NOT_NULL
has_pictures:       (TINYINT)       NULL        DEFAULT(0)
image_url:          VARCHAR(255)    NULL
is_published:       (TINYINT)       NOT_NULL    DEFAULT(0)
