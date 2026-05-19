<template>
    <v-app>
        <v-main>
            <v-container>
                <v-row>
                    <v-col cols="12">
                        <v-text-field 
                            label="Student No." 
                            variant="outlined"
                            clearable
                        ></v-text-field>
                    </v-col>
                    <v-col cols="12"
                            md="4">
                        <v-text-field 
                            label="Last Name" 
                            variant="outlined"
                            clearable
                        ></v-text-field>
                    </v-col>
                   <v-col cols="12"
                            md="4">
                        <v-text-field 
                            label="First Name" 
                            variant="outlined"
                            clearable
                        ></v-text-field>
                    </v-col>
                    <v-col cols="12"
                            md="4">
                        <v-text-field 
                            label="Middle Name" 
                            variant="outlined"
                            clearable
                        ></v-text-field>
                    </v-col>
                    <v-col cols="12"
                            md="4">
                        <v-combobox
                             chips
                             label="Course"
                            :items="['DCT' , 'BSCS' ,]"
                            clearable
                            ></v-combobox>
                    </v-col>
                    <v-col cols="12"
                            md="4">
                        <v-combobox
                             chips
                             label="Year"
                            :items="['1st Year' , '2nd Year' , '3rd Year' , '4th Year']"
                            clearable
                            ></v-combobox>
                    </v-col>
                    <v-col cols="12"
                            md="4">
                        <v-combobox
                             chips
                             label="Section"
                            :items="['A', 'B', 'C', 'D',]"
                            clearable
                            ></v-combobox>
                    </v-col>
                    <v-col cols="12"
                            md="4">
                        <v-text-field 
                            label="Address:" 
                            variant="outlined"
                            clearable
                        ></v-text-field>
                    </v-col>
                    <v-col cols="12"
                            md="4">
                        <v-text-field 
                            label="Contact No:" 
                            variant="outlined"
                            placeholder="#"
                            clearable
                        ></v-text-field>
                    </v-col>
                    <v-col cols="12"
                            md="4">
                        <v-combobox
                             chips
                             label="Gender"
                            :items="['Male' , 'Female' , 'LGBTQ' ,]"
                            clearable
                        ></v-combobox>
                    </v-col>
                </v-row>
            </v-container>
        </v-main>
    </v-app>
</template>