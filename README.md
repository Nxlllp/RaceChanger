# RaceChanger
mod.game.me.class == ('職業')
	DataCenterの職表記にする必要あり。
	
	ウォーリアー = warrior	ランサー = lancer	 スレイヤー = slayer	バーサーカー = berserker

	ソーサラー = sorcerer	ガンナー = engineer アーチャー = archer	プリースト = priest		
	
	エレメンタリスト = elementalist

	ソウルリーパー = soulless ファイター = fighter	忍者 = assassin	ムーングレイバー = glaiver
		

int32     templateId  # For players the convention is 1XXYY (X = 1 + race*2 + gender, Y = 1 + class). See C_CREATE_USER

C_CREATE_USER---

int32     gender  0 = Male, 1 = Female

int32     race    0 = Human, 1 = High Elf, 2 = Aman, 3 = Castanic, 4 = Popori/Elin, 5 = Baraka

   class   0 = Warrior, 1 = Lancer, 2 = Slayer, 3 = Berserker, 4 = Sorcerer, 5 = Archer
	6 = Priest, 7 = Mystic, 8 = Reaper, 9 = Gunner, 10 = Brawler, 11 = Ninja, 12 = Valkyrie
				 
例： エリーンガンナー 1 XX YY

				XX = 1 + 4(Popori/Elin)*2 + 1(gender) + = 10
				
				YY = 1 + 9 = 10
				
				 1 10 10
				 


パンツを見せること、それが…　大宇宙の誇り 
