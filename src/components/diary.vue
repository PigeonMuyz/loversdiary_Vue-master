<template>
    <var-sticky>
        <var-app-bar title="友人记" style="margin-bottom: 10px">
            <template #right>
                <var-button
                    round
                    text
                    color="transparent"
                    text-color="#ffffff"
                    @click="toggleTheme"
                >
                    <var-icon name="menu" :size="24" />
                </var-button>
            </template>
        </var-app-bar>
    </var-sticky>
		
		<var-tabs
			elevation
			v-model:active="active"
		>
			<var-tab>我记</var-tab>
			<var-tab>TA记</var-tab>
			<var-tab>大家记</var-tab>
		</var-tabs>
		<var-tabs-items v-model:active="active">
            <var-tab-item>
                <var-space direction="column" style="margin-top: 10px;">
                    <var-row>
                        <var-col :span="1"></var-col>
                        <var-col :span="22">
                            <var-card title="2022年4月20日 日记" subtitle="Author: Muyz" description="阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴"></var-card>
                        </var-col>
                        <var-col :span="1"></var-col>
                    </var-row>
                    <var-row>
                        <var-col :span="1"></var-col>
                        <var-col :span="22"><var-card title="2022年4月20日 日记" subtitle="Author: Muyz" description="阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴"></var-card></var-col>
                        <var-col :span="1"></var-col>
                    </var-row>
                    <var-row>
                        <var-col :span="1"></var-col>
                        <var-col :span="22"><var-card title="2022年4月20日 日记" subtitle="Author: Muyz" description="阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴"></var-card></var-col>
                        <var-col :span="1"></var-col>
                    </var-row>
                    <var-row>
                        <var-col :span="1"></var-col>
                        <var-col :span="22"><var-card title="2022年4月20日 日记" subtitle="Author: Muyz" description="阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴"></var-card></var-col>
                        <var-col :span="1"></var-col>
                    </var-row>
                    <var-row>
                        <var-col :span="1"></var-col>
                        <var-col :span="22"><var-card title="2022年4月20日 日记" subtitle="Author: Muyz" description="阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴"></var-card></var-col>
                        <var-col :span="1"></var-col>
                    </var-row>
                    <var-row>
                        <var-col :span="1"></var-col>
                        <var-col :span="22"><var-card title="2022年4月20日 日记" subtitle="Author: Muyz" description="阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴"></var-card></var-col>
                        <var-col :span="1"></var-col>
                    </var-row>
                    <var-row>
                        <var-col :span="1"></var-col>
                        <var-col :span="22"><var-card title="2022年4月20日 日记" subtitle="Author: Muyz" description="阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴"></var-card></var-col>
                        <var-col :span="1"></var-col>
                    </var-row>
                </var-space>
            </var-tab-item>
            <var-tab-item>
                <var-space direction="column" style="margin-top: 10px;">
                    <var-row>
                        <var-col :span="1"></var-col>
                        <var-col :span="22">
                            <var-card title="2022年4月21日 日记" subtitle="Author: Muyz" description="阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴"></var-card>
                        </var-col>
                        <var-col :span="1"></var-col>
                    </var-row>
                    <var-row>
                        <var-col :span="1"></var-col>
                        <var-col :span="22"><var-card title="2022年4月20日 日记" subtitle="Author: Muyz" description="阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴"></var-card></var-col>
                        <var-col :span="1"></var-col>
                    </var-row>
                    <var-row>
                        <var-col :span="1"></var-col>
                        <var-col :span="22"><var-card title="2022年4月20日 日记" subtitle="Author: Muyz" description="阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴"></var-card></var-col>
                        <var-col :span="1"></var-col>
                    </var-row>
                </var-space>
            </var-tab-item>
            <var-tab-item>
                <var-space direction="column" style="margin-top: 10px;">
                    <var-row>
                        <var-col :span="1"></var-col>
                        <var-col :span="22">
                            <var-card title="2022年4月20日 日记" subtitle="Author: Muyz" description="阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴"></var-card>
                        </var-col>
                        <var-col :span="1"></var-col>
                    </var-row>
                    <var-row>
                        <var-col :span="1"></var-col>
                        <var-col :span="22"><var-card title="2022年4月20日 日记" subtitle="Author: Muyz" description="阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴"></var-card></var-col>
                        <var-col :span="1"></var-col>
                    </var-row>
                    <var-row>
                        <var-col :span="1"></var-col>
                        <var-col :span="22"><var-card title="2022年4月20日 日记" subtitle="Author: Muyz" description="阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴阿巴巴巴巴巴巴巴巴巴巴巴"></var-card></var-col>
                        <var-col :span="1"></var-col>
                    </var-row>
                </var-space>
            </var-tab-item>
        </var-tabs-items>
</template>
<script>
import dark from '@varlet/ui/es/themes/dark'
import { StyleProvider } from '@varlet/ui'
export default{
    name: "diaryCompent",
    data(){
        return{
            active: 0
        }
    },
    setup() {
        let currentTheme
        const toggleTheme = () => {
        currentTheme = currentTheme ? null : dark
        StyleProvider(currentTheme)
        }
        return { toggleTheme }
    }
}
</script>