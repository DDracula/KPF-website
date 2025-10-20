```paradox
technologies = {

    tech_logistics_enhancement = {
        allow = { always = no }

        logistics_company = {
			supply_consumption_factor = -0.05
		    fuel_consumption_factor = -0.025
		}
    }

    tech_radio_advantage = { 
        allow = { always = no }

        signal_company = {
			initiative = 0.2
            default_morale = 0.2
            max_strength = 0.25
		}
    }

    tech_rapid_support_forces = {
        allow = { always = no }

        assault_battalion = {
            soft_attack = 0.1 
		    breakthrough = 0.15
        }
    }

    tech_battlefield_angels = {
        allow = { always = no }

        field_hospital = {
            supply_consumption = 0.05
            battalion_mult = {
                category = category_all_infantry
                max_strength = 0.15
            }
        }
    }

    tech_elite_field_engineer_regiment = {
        allow = { always = no }

        engineer = {
            entrenchment = 0.75
            fort = {
				defence = 0.15
				attack = 0.15
			}
        }
    }

    tech_organic_army = {
        allow = { always = no }

        category_all_infantry = {
			max_organisation = 5
            defense = 0.05
		}
    }

    tech_everyone_commissar = {
        allow = { always = no }

        military_police = {
            default_morale = 0.2
            battalion_mult = {
                category = category_all_infantry
                soft_attack = 0.10
                initiative = 0.05
                max_strength = 0.05
            }
        }
    }

    tech_beat_enemy_with_single_blow = {
        allow = { always = no }

        category_army = {
			breakthrough = 0.1
			soft_attack = 0.1
		}
        category_support_battalions = {
            breakthrough = 0.05
			soft_attack = 0.15
		}
    }

    tech_fully_equipped = {
        allow = { always = no }

        elite_infantry = {
            breakthrough = 0.15
            max_strength = 0.1
            max_organisation = 10
			soft_attack = 0.15
            hard_attack = 0.15
            supply_consumption = 0.2
        }
    }

    tech_regularization_of_militia = {
        allow = { always = no }

        militia = {
            recon = 0.15
            max_organisation = 10
            max_strength = 0.1
			soft_attack = 0.1
            hard_attack = 0.05
            supply_consumption = -0.1
            urban = {
				attack = 0.1
                defence = 0.2
			}
        }
    }

    tech_chameleon_warfare = {
        allow = { always = no }

        on_research_complete = {
            custom_effect_tooltip = tech_chameleon_warfare_tt
        }
        show_effect_as_desc = yes

        category_light_infantry = {
            urban = {
                defence = 0.05
                movement = 0.03
            }
            snow = {
                defence = 0.05
				movement = 0.03
			}
			forest = {
                defence = 0.05
				movement = 0.03
			}
			hills = {
                defence = 0.05
				movement = 0.03
			}
			mountain = {
                defence = 0.05
				movement = 0.03
			}
			marsh = {
                defence = 0.05
				movement = 0.03
			}
			plains = {
                defence = 0.05
				movement = 0.03
			}
			river = {
                defence = 0.05
				movement = 0.03
			}
        }
    }

    tech_pursui_oriented_guerrilla = {
        allow = { always = no }

        category_light_infantry = {
            recon = 0.1
            initiative = 0.1
            soft_attack = 0.1
            supply_consumption = -0.05
        }
    }

    tech_precision_killing = {
        allow = { always = no }

        artillery = {
            soft_attack = 0.25
            hard_attack = 0.1
            supply_consumption = 0.1
        }
    }

    tech_conquering_the_hills = {
        allow = { always = no }

        on_research_complete = {
            custom_effect_tooltip = tech_conquering_the_hills_tt
        }
        show_effect_as_desc = yes

        category_mountaineers = {
            recon = 0.1

            hills = {
                attack = 0.15
                defence = 0.1
                movement = 0.15
            }
            mountain = {
                attack = 0.15
                defence = 0.1
                movement = 0.15
            }
        }
    }

    tech_across_the_ocean = {
        allow = { always = no }

        on_research_complete = {
            custom_effect_tooltip = tech_across_the_ocean_tt
        }
        show_effect_as_desc = yes

        category_marines = {
            breakthrough = 0.1
            recon = 0.1

            marsh = {
                attack = 0.1
                defence = 0.05
                movement = 0.1
            }
            river = {
                attack = 0.1
                defence = 0.05
                movement = 0.1
            }
            amphibious = {
                attack = 0.1
                defence = 0.05
                movement = 0.1
            }
        }
    }

    tech_vanguard_task_force = {
        allow = { always = no }

        engineer = {
            breakthrough = 0.2
            fort = {
				attack = 0.2
                movement = 0.15
			}
        }

        assault_battalion = {
            breakthrough = 0.2
            fort = {
				attack = 0.2
                movement = 0.15
			}
        }
    }

    tech_rock_firm = {
        allow = { always = no }

        category_front_line = {
            supply_consumption = -0.05
            default_morale = 0.1
            max_strength = 0.1
            entrenchment = 0.5
        }
    }

    tech_put_to_our_advantage = {
        allow = { always = no }

        maintenance_company = {
            max_strength = 0.1
            reliability_factor = 0.1
            equipment_capture_factor = 0.1
        }
    }

    tech_land_cruiser = {
        allow = { always = no }

        amphibious_armor = {
            breakthrough = 0.1
            recon = 0.1
            supply_consumption = -0.05

            marsh = {
                attack = 0.1
                defence = 0.05
                movement = 0.1
            }
            river = {
                attack = 0.1
                defence = 0.05
                movement = 0.1
            }
            amphibious = {
                attack = 0.1
                defence = 0.05
                movement = 0.1
            }
        }
    }

    tech_birds_nest_on_the_sea = {
        allow = { always = no }

        carrier = {
            carrier_size = 0.5
        }
    }

    tech_handling_butchers_cleaver_with_ease = {
        allow = { always = no }

        battleship = {
            max_organisation = 10
        }
        battle_cruiser = {
			max_organisation = 10
		}
        light_cruiser = {
            max_organisation = 10
        }
		heavy_cruiser = {
			max_organisation = 10
		}
        destroyer = {
            max_organisation = 10
        }
    }

    tech_wild_goose_breakthrough = {
        allow = { always = no }

        battleship = {
            water_fjords = {
                attack = 0.15
                movement = 0.1
            }
            water_shallow_sea = {
                attack = 0.15
                movement = 0.1
            }
            water_deep_ocean = {
                attack = 0.15
                movement = 0.1
            }
        }
        battle_cruiser = {
			water_fjords = {
                attack = 0.15
                movement = 0.1
            }
            water_shallow_sea = {
                attack = 0.15
                movement = 0.1
            }
            water_deep_ocean = {
                attack = 0.15
                movement = 0.1
            }
		}
        destroyer = {
            water_fjords = {
                attack = 0.15
                movement = 0.1
            }
            water_shallow_sea = {
                attack = 0.15
                movement = 0.1
            }
            water_deep_ocean = {
                attack = 0.15
                movement = 0.1
            }
        }
        submarine = {
            water_fjords = {
                attack = 0.15
                movement = 0.1
            }
            water_shallow_sea = {
                attack = 0.15
                movement = 0.1
            }
            water_deep_ocean = {
                attack = 0.15
                movement = 0.1
            }
        }
    }

    tech_stealth_parachuting = {
        allow = { always = no }

        paratroopers = {
            soft_attack = 0.05
            hard_attack = 0.05
            max_organisation = 15
            max_strength = 0.1
        }
    }
}