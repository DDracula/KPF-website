```paradox
buildings = {
    landmark_peoples_academy_of_sciences = {
		dlc_allowed = { has_dlc = Gotterdammerung }
		show_on_map = 1
		base_cost = 20000
		damage_factor = 0 
		icon_frame = 22
		value = 5
		
		is_buildable = no
		disable_grow_animation = yes
		repair_speed_factor = 0.15
		spawn_point = landmark_spawn
		only_display_if_exists = yes
		special_icon = GFX_berlin_reichstag_icon_small
		level_cap = {
			province_max = 1
		}
		always_shown = yes
		show_modifier = yes
		country_modifiers = {
			enable_for_controllers = { FRA }
			modifiers = {
				research_speed_factor = 0.15
				monthly_change_ei = 0.5
			}
		}
	}

	landmark_national_military_academy = {
		dlc_allowed = { has_dlc = Gotterdammerung }
		show_on_map = 1
		base_cost = 20000
		damage_factor = 0 # This building can't be damaged by regular strat bombing
		icon_frame = 22
		value = 5
		
		is_buildable = no
		disable_grow_animation = yes
		spawn_point = landmark_spawn
		repair_speed_factor = 0.15
		only_display_if_exists = yes
		special_icon = GFX_berlin_reichstag_icon_small
		level_cap = {
			province_max = 1
		}
		always_shown = yes
		show_modifier = yes
		country_modifiers = {
			enable_for_controllers = { FRA }
			modifiers = {
				experience_gain_army_factor = 0.1
				max_planning_factor = 0.025
				army_leader_start_planning_level = 1
				monthly_change_atheory1 = 0.3
				monthly_change_atheory2 = 0.3
				monthly_change_atheory3 = 0.3
				monthly_change_atheory4 = 0.3
				monthly_change_atheory5 = 0.3
				monthly_change_atheory6 = 0.3
				monthly_change_atheory7 = 0.3
				monthly_change_atheory8 = 0.3
			}
		}
	}

	landmark_brest_naval_college = {
		dlc_allowed = { has_dlc = Gotterdammerung }
		show_on_map = 1
		base_cost = 20000
		damage_factor = 0 # This building can't be damaged by regular strat bombing
		icon_frame = 22
		value = 5
		
		is_buildable = no
		disable_grow_animation = yes
		spawn_point = landmark_spawn
		repair_speed_factor = 0.15
		only_display_if_exists = yes
		special_icon = GFX_berlin_reichstag_icon_small
		level_cap = {
			province_max = 1
		}
		always_shown = yes
		show_modifier = yes
		country_modifiers = {
			enable_for_controllers = { FRA }
			modifiers = {
				experience_gain_navy_factor = 0.15
				navy_advisor_cost_factor = -0.25
				critical_receive_chance = -0.25
			}
		}
	}

	landmark_alpine_hollow_experimental_base = {
		dlc_allowed = { has_dlc = Gotterdammerung }
		show_on_map = 1
		base_cost = 20000
		damage_factor = 0 # This building can't be damaged by regular strat bombing
		icon_frame = 22
		value = 5
		
		is_buildable = no
		disable_grow_animation = yes
		spawn_point = landmark_spawn
		repair_speed_factor = 0.15
		only_display_if_exists = yes
		special_icon = GFX_berlin_reichstag_icon_small
		level_cap = {
			province_max = 1
		}
		always_shown = yes
		show_modifier = yes
		country_modifiers = {
			enable_for_controllers = { FRA }
			modifiers = {
				experience_gain_air_factor = 0.1
				specialization_air_speed_factor = 0.25
				air_equipment_upgrade_xp_cost = -0.25
			}
		}
	}
}