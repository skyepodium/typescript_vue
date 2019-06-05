<template>
    <div>
        <input type="" v-model="message">    
        <div>{{ message }}</div>
    </div>
</template>

<script lang="ts">
import {Component, Vue} from 'vue-property-decorator';

@Component // 클래스 인스턴스를 컴포넌트 인스턴스로 사용하기 위함
export default class Message extends Vue {
    message: string = '메세지를 입력해주세요'
}
</script>

