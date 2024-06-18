Skrzynki tekkena z clowns.cool, w pelni odkodowane. Leak bo idioci zaczynają to sprzedawać i wpierdalają te skrzynki "odkodowane" z jakimiś backdoorami w zestawie ;)

tabelka do bazy:
<br>CREATE TABLE `cases_coins` (
  `license` varchar(255) NOT NULL,
  `SilverCoins` int(11) NOT NULL DEFAULT 0,
  `GoldCoins` int(11) NOT NULL DEFAULT 0
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

ALTER TABLE `cases_coins`
  ADD PRIMARY KEY (`license`);
COMMIT;
