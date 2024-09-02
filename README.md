# Dreamy_Desserts
This repository is intended for the Responsive Shopping Cart system of Desserts with admin panel and checkout order system using HTML, CSS ,JS, PHP and MySQL database.

#### Table structure for Database
Database: `dreamy_desserts`

CREATE TABLE `cart` ( `id` int(255) EXTRA AUTO_INCREMENT, `name` varchar(255), `price` varchar(255), `image` varchar(255), `quantity` int(255) )

CREATE TABLE `order` ( `id` int(255) EXTRA AUTO_INCREMENT, `name` varchar(100), `number` varchar(12), `email` varchar(255), `method` int(100), `flat` varchar(100), `street` varchar(100), `city` varchar(100), `state` varchar(100), `country` varchar(100), `pin_code` int(10), `total_products` varchar(255), `total_price` varchar(255) )

CREATE TABLE `products` ( `id` int(255) EXTRA AUTO_INCREMENT, `name` varchar(255), `price` varchar(255), `image` varchar(255) )
