<template>
    <div class="az-container">
        <slot/>
    </div>
</template>

<script>
    export default {}
</script>

<style lang="stylus">

    .primary--text
        color: #777777 !important

    .v-list
        padding: 0
        &__tile
            color: #7f7f7f
            height: 38px
            &__title
                font-size: 14px

            &__action
                min-width: unset
                padding-right: 10px
                .material-icons
                    font-size: 13px

    .container.grid-list-xl
        padding: 0

    .container.grid-list-xl .layout .flex
        padding: 0 10px

    .az-tabs
        margin: 20px
        .v-tabs__div
            text-transform: none

        .v-tabs__item--active
            color: #d28a2c !important
            font-weight: bold
            border-bottom: 1px solid white
            border-left: 1px solid #ccc
            border-right: 1px solid #ccc
            border-top: 1px solid #ccc
            border-radius: 2px

        .v-tabs__item
            color: #777777
            padding: 10px 20px

        .v-tabs__slider-wrapper
            display: none

        .v-tabs__container
            border-bottom: 1px solid #ccc

        .v-text-field__slot
            font-size: 14px

        .v-select__selections
            font-size: 14px


    .v-content__wrap
        background-color: #eee

    .az-container
        margin: 20px
        background-color: white

        .az-resume-bar
            background-color: #3a6861
            height: 60px

        .az-table-list
            thead
                border: none
                tr:first-child
                    height: 35px !important
                    border-bottom: 2px solid #e9e9e9 !important

                tr th
                    color: #3a6861 !important
                    font-weight: bold
                    padding: 0 10px !important

                tbody tr
                    &:nth-child(even)
                        background-color: #f9f9f9

    tbody tr
        border-bottom: 1px solid #e9e9e9 !important
        td
            height: 40px
            color: #777777
            font-size: 13px
            font-weight: normal
            padding: 0 20px !important

        .table-actions a i
            font-size: 20px
            color: #888

        .table-actions a
            margin-left: 10px

</style>
