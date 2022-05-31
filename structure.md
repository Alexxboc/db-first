# Car dealership



## Model: Used car



## Table: Used cars



- ID:                            BIGINT                PRIMARYKEY(NOTNULL, AUTOINCREMENTS, UNIQUE)

- Title:                         VARCHAR(200)          NOT NULL

- Category:                      VARCHAR(50)           NULL

- Model:                         VARCHAR(20)           NOTNULL, INDEX

- Brand:                         VARCHAR(20)           NOTNULL, INDEX

- Year:                          YEAR                  NULL

- Km traveled:                   FLOAT(8,2)            NULL

- Car review:                    YEAR                  NULL

- Price:                         DECIMAL(8,2)          NOTNULL

- Special_price:                 DECIMAL(8,2)          NULL

- Discount:                      FLOAT(3,1)            NULL

- License plate:                 VARCHAR(7)            NULL

- Description:                   TEXT                  NULL

- Technical specifications:      TEXT                  NULL

- Sizes:                         VARCHAR(20)           NULL

- Accessories:                   TEXT                  NULL

- Cover_image:                   VARCHAR(255)          NULL

- Thumbnail_image                VARCHAR(255)          NULL

- Lowered rate:                  TINYINT               NULL

- Financing:                     TINYINT               NULL

- Quantity:                      TINYINT               NOTNULL DEFAULT(0)

- Note:                          TEXT                  NULL

- Created_at:                    TIMESTAMP             NOTNULL 

- Updated_at:                    TIMESTAMP             NOTNULL 

- Meta_title:                    VARCHAR(200)          NULL

- Meta_keywords:                 VARCHAR(50)           NULL

- Meta_description:              TEXT                  NULL