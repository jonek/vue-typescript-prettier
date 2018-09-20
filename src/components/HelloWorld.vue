<script lang="ts">
import Component from 'vue-class-component';
import Vue from 'vue';

let foo = 1;
let bar = 2;
let baz = foo / bar * 3;

@Component
export default class HelloWorld extends Vue {}
</script>
