# Vuetify-Tooltip
the given css adda an arrow to the vuetify tootltip


## Contributions
All contributions and suggestions are welcome

## Usage

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
