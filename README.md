# Vuetify-Tooltip
the given css add an arrow to the vuetify tootltip


## Contributions
All contributions and suggestions are welcome

## Usage

this how u can implement it


                    <v-tooltip top content-class="primary tooltip-top">
                            <template v-slot:activator="{ on, attrs }">
                                <v-btn
                                    v-bind="attrs"
                                    v-on="on"
                                    icon
                                    color="primary"
                                    @click="editItem(item)"
                                >
                                    <v-icon>mdi-pencil</v-icon>
                                </v-btn>
                            </template>
                            <span>Edit Details</span>
                        </v-tooltip>


![image](https://user-images.githubusercontent.com/20104015/127085657-a5635a86-3b27-4689-b737-1b608d9ffd42.png)
