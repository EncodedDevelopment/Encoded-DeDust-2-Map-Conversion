# Encoded-DeDust-2-Map-Conversion
DeDust map from CS 1.6 converted to fivem for Nass_Paintball 


added in the resource file a statement included in valve giving full permission on their map being ripped and used in any game if modifications were made.

The map uses custom materials and custom colissions to work with fivem and formated to a rage engine stream format.

Installation:

Head to nass_paintball/html/images
copy the dust.png to that location

head to nass_paintball/config.lua and add the following code

 ["Dust Map"] = {
        arena = {
            enabled = true, -- Set this to false if you are using your own custom map
            category = "dystopian", -- dystopian | scifi | wasteland
            map = 5, -- 1 - 10
        },
        image = "dust.png",
        radius = 300,
        center = vector3(3869.38, 1492.61, 36.63),
        radius = 300,
        spawnPoints = {
            [1] = {
                vector4(3844.04, 1525.03, 38.34, 149.07),
                vector4(3842.49, 1524.62, 38.34, 194.98),
                vector4(3840.72, 1526.24, 38.34, 283.14),
                vector4(3839.53, 1524.45, 38.34, 197.63),
                vector4(3839.95, 1521.99, 38.34, 199.32),
                vector4(3838.94, 1520.33, 38.34, 232.69),
                vector4(3841.69, 1519.63, 38.34, 258.96),
                vector4(3844.75, 1518.83, 38.34, 239.62),
            },
            [2] = {
                vector4(3885.43, 1519.19, 35.46, 97.16),
                vector4(3882.87, 1518.87, 35.46, 210.65),
                vector4(3880.72, 1518.64, 35.46, 105.42),
                vector4(3878.01, 1517.81, 35.46, 119.18),
                vector4(3878.06, 1516.33, 35.46, 148.43),
                vector4(3880.42, 1515.99, 35.46, 233.75),
                vector4(3882.07, 1516.08, 35.46, 237.37),
                vector4(3884.79, 1516.06, 35.46, 240.77),
            },
            [3] = {
                vector4(3881.37, 1523.11, 39.49, 242.88),
                vector4(3883.31, 1523.07, 39.49, 272.22),
                vector4(3885.12, 1522.73, 39.49, 252.59),
                vector4(3884.93, 1521.2, 39.49, 200.18),
                vector4(3882.88, 1520.01, 39.49, 151.44),
                vector4(3883.93, 1518.84, 39.49, 224.95),
                vector4(3883.41, 1516.61, 39.49, 229.39),
                vector4(3884.7, 1515.34, 39.49, 269.69),
            },
            [4] = {
                vector4(3904.33, 1475.62, 34.36, 98.25),
                vector4(3902.96, 1475.9, 34.31, 14.97),
                vector4(3901.27, 1476.0, 34.31, 31.27),
                vector4(3903.11, 1477.5, 34.31, 339.75),
                vector4(3900.79, 1477.65, 34.31, 309.64),
                vector4(3902.03, 1479.21, 34.48, 312.24),
                vector4(3904.75, 1479.52, 34.75, 277.39),
                vector4(3899.86, 1480.42, 34.93, 354.13),
            },
            [5] = {
                vector4(3889.47, 1468.36, 37.77, 50.86),
                vector4(3889.01, 1470.13, 37.77, 95.72),
                vector4(3889.3, 1472.43, 37.77, 100.71),
                vector4(3889.2, 1473.64, 37.77, 133.76),
                vector4(3887.42, 1473.67, 37.77, 74.05),
                vector4(3887.23, 1471.89, 37.77, 128.06),
                vector4(3885.86, 1470.88, 37.77, 172.33),
                vector4(3884.17, 1468.68, 37.77, 131.58),
            },
            [6] = {
                vector4(3846.21, 1468.91, 40.07, 223.88),
                vector4(3847.81, 1469.2, 40.07, 334.38),
                vector4(3849.51, 1469.37, 40.07, 331.91),
                vector4(3852.6, 1468.17, 40.07, 280.46),
                vector4(3854.08, 1467.6, 40.07, 82.77),
                vector4(3854.8, 1465.94, 40.07, 122.56),
                vector4(3852.99, 1465.23, 40.07, 122.53),
                vector4(3850.46, 1465.74, 40.07, 93.2),
            },
            [7] = {
                vector4(3845.94, 1499.2, 38.34, 132.94),
                vector4(3844.26, 1498.25, 38.34, 223.26),
                vector4(3845.03, 1498.19, 38.34, 109.8),
                vector4(3846.01, 1496.75, 38.34, 212.74),
                vector4(3844.31, 1496.25, 38.34, 155.72),
                vector4(3843.1, 1498.27, 38.34, 27.14),
                vector4(3843.55, 1498.98, 38.34, 202.78),
                vector4(3844.47, 1497.28, 38.34, 209.4),
            },
            [8] = {
                vector4(3862.42, 1498.0, 35.75, 326.18),
                vector4(3863.8, 1498.01, 35.75, 10.33),
                vector4(3864.87, 1497.84, 35.75, 11.49),
                vector4(3865.79, 1497.97, 35.75, 13.37),
                vector4(3862.18, 1499.39, 35.75, 92.93),
                vector4(3862.45, 1498.94, 35.75, 71.25),
                vector4(3863.2, 1500.37, 35.75, 337.34),
                vector4(3865.06, 1500.6, 35.75, 326.81),
            },
        },
        flags = {
            [1] = vector4(3847.23, 1522.33, 37.77, 219.27),
            [2] = vector4(3897.41, 1518.02, 39.49, 170.82),
        },
        animation = {
            enabled = true,
            opening = {
                firstCamPos = vector4(3868.53, 1513.04, 35.46, 280.38),
                secondCamPos = vector4(3864.38, 1511.83, 35.46, 284.08),
                pedPos = vector4(3872.29, 1512.94, 35.46, 92.2),
            },
            winning = {
                firstCamPos = vector4(3868.53, 1513.04, 35.46, 280.38),
                secondCamPos = vector4(3864.38, 1511.83, 35.46, 284.08),
                pedPos = vector4(3872.29, 1512.94, 35.46, 92.2),
            },
        }
    },

Why C.S 1.6 ?

Its an extremely optimized model and will garantee zero performance impact

The map is best desgined for small teams  1v1 to 4v4 but can go up to full lobby in Nass Paintball
