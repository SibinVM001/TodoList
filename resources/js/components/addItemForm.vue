<template>
    <div class="addItem">
        <input type="text" class="input" placeholder="Add Todo">
        <button class="addButton"></button>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    .addItem {
        display: flex;
        justify-content: center;
        align-items: center;
        margin-bottom: 25px;
    }

    .input {
        border: 4px solid blue;
        border-bottom-left-radius: 4px;
        border-top-left-radius: 4px;
        border-width: 1px;
        outline: none;
        padding: 5px;
        height: 30px;
        width: 100%;
    }

    .addButton {
        height: 42px;
        width: 42px;
        border: 4px solid blue;
        border-bottom-right-radius: 4px;
        border-top-right-radius: 4px;
        border-width: 1px;
        background-color: white;
    }
</style>