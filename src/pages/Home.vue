<script setup>
import Logo from '@/components/Logo.vue'
import IconUp from '@/components/icons/up.vue'
import IconBitcoin from '@/components/icons/bitcoin.vue'
import IconUsd from '@/components/icons/usd.vue'
import IconBots from '@/components/icons/bots.vue'
import IconCalendar from '@/components/icons/calendar.vue'
import IconSubtract from '@/components/icons/subtract.vue'
import IconPay from '@/components/icons/pay.vue'
import IconCloud from '@/components/icons/cloud.vue'
import IconSteam from '@/components/icons/steam.vue'
import IconSettings from '@/components/icons/settings.vue'
import IconCart from '@/components/icons/cart.vue'
import IconUser from '@/components/icons/user.vue'
import IconArrow from '@/components/icons/arrow.vue'
import Wave from '@/components/ilustrations/wave.vue'
import Globus from '@/components/ilustrations/globus.vue'
</script>
<template>
    <div class="bg-[#1a1a1a] h-full pb-10">
        <div class="container space-y-10 px-10 md:px-0">
            <div class="flex justify-start py-8">
                <Logo class="fill-white h-[44px]" />
            </div>

            <div class="grid lg:grid-cols-3 grid-cols-1 xl:grid-cols-4 gap-4 mt-10">



                <div class="md:hidden px-14 mb-40 text-center">
                    <Globus />
                    <p class="text-white text-sm">Waxpeer online & status</p>

                    <p class="bg-gradient-to-b from-white to-transparent bg-clip-text text-transparent text-[30px]">
                        12698</p>
                    <p class="text-[#BABAC2]/50 text-sm">extension</p>


                    <div class="w-full flex justify-center">
                        <div
                            class="min-h-[50px] w-px self-stretch bg-gradient-to-tr from-transparent via-neutral-500 to-transparent opacity-25 dark:via-neutral-400">
                        </div>
                    </div>

                    <p class="bg-gradient-to-b from-white to-transparent bg-clip-text text-transparent text-[30px]">
                        5898</p>
                    <p class="text-[#BABAC2]/50 text-sm">desktop</p>

                    <div class="w-full flex justify-center">
                        <div
                            class="min-h-[50px] w-px self-stretch bg-gradient-to-tr from-transparent via-neutral-500 to-transparent opacity-25 dark:via-neutral-400">
                        </div>
                    </div>

                    <p class="bg-gradient-to-b from-white to-transparent bg-clip-text text-transparent text-[30px]">
                        25697</p>
                    <p class="text-[#BABAC2]/50 text-sm">mobile</p>
                </div>

                <div class="card group">
                    <div class="flex justify-start items-center gap-2">
                        <IconUp class="bg-[#262626] rounded-full w-6 h-6 p-1" />
                        <span class="text-white text-sm">Uptime</span>

                        <IconArrow class="arrow group-hover:opacity-100" />
                    </div>

                    <p class="text-[#BABAC2]/50 text-sm ml-8 py-3">Uptime over the past 24 hours</p>

                    <div class="flex justify-between items-center gap-2 ml-8 py-6 ">
                        <span
                            class="bg-gradient-to-b from-white to-transparent bg-clip-text text-transparent text-[30px]">97.83%</span>
                        <Wave />
                    </div>
                </div>

                <div class="hidden md:flex relative px-14 col-span-2 justify-between items-center">
                    <div>
                        <p class="text-white text-sm">Waxpeer online & status</p>

                        <div class="flex w-full mt-6">
                            <div class="text-left">
                                <p
                                    class="bg-gradient-to-b from-white to-transparent bg-clip-text text-transparent text-[30px]">
                                    12698</p>
                                <p class="text-[#BABAC2]/50 text-sm">extension</p>
                            </div>

                            <div class="text-left border-x border-[#333333] px-6 mx-6">
                                <p
                                    class="bg-gradient-to-b from-white to-transparent bg-clip-text text-transparent text-[30px]">
                                    5898</p>
                                <p class="text-[#BABAC2]/50 text-sm">desktop</p>
                            </div>

                            <div class="text-left">
                                <p
                                    class="bg-gradient-to-b from-white to-transparent bg-clip-text text-transparent text-[30px]">
                                    25697</p>
                                <p class="text-[#BABAC2]/50 text-sm">mobile</p>
                            </div>
                        </div>
                    </div>

                    <Globus />
                </div>

                <div class="card group">
                    <div class="flex justify-start items-center gap-2">
                        <IconUp class="bg-[#262626] rounded-full w-6 h-6 p-1" />
                        <span class="text-white text-sm">Current date</span>

                        <IconArrow class="arrow group-hover:opacity-100" />
                    </div>

                    <p class="text-[#BABAC2]/50 text-sm ml-8 py-3">Current date and time</p>

                    <div class="flex justify-between items-end gap-2 ml-8 py-6 ">
                        <span
                            class="bg-gradient-to-b from-white to-transparent bg-clip-text text-transparent text-[30px]">08.06.2022</span>
                        <p class="text-[#BABAC2]/50 text-sm">19:55:20</p>
                    </div>
                </div>

                <div class="card group">
                    <div class="flex justify-start items-center gap-2">
                        <IconBitcoin class="bg-[#262626] rounded-full w-6 h-6 p-1" />
                        <span class="text-white text-sm">Withdrawal status</span>

                        <IconArrow class="arrow group-hover:opacity-100" />
                    </div>

                    <p class="text-[#BABAC2]/50 text-sm ml-8 py-3">Connected cryptocurrencies</p>

                    <div class="flex justify-end items-center py-6">
                        <IconSubtract />
                    </div>
                </div>

                <div class="card group">
                    <div class="flex justify-start items-center gap-2">
                        <IconUsd class="bg-[#262626] rounded-full w-6 h-6 p-1" />
                        <span class="text-white text-sm">Buy items</span>

                        <IconArrow class="arrow group-hover:opacity-100" />
                    </div>

                    <p class="text-[#BABAC2]/50 text-sm ml-8 py-3">Time from the last purchase</p>

                    <div class="flex justify-end items-center py-6">
                        <span
                            class="bg-gradient-to-b from-white to-transparent bg-clip-text text-transparent text-[30px]">25
                            sec</span>
                    </div>
                </div>

                <div class="card group">
                    <div class="flex justify-start items-center gap-2">
                        <IconBots class="bg-[#262626] rounded-full w-6 h-6 p-1" />
                        <span class="text-white text-sm">Waxpeer pay bots</span>

                        <IconArrow class="arrow group-hover:opacity-100" />
                    </div>

                    <p class="text-[#BABAC2]/50 text-sm ml-8 py-3">The number of avaliable bots on Wxpeer pay</p>

                    <div class="flex justify-end items-center py-6">
                        <span
                            class="bg-gradient-to-b from-white to-transparent bg-clip-text text-transparent text-[30px]">
                            259 bots
                        </span>
                    </div>
                </div>

                <div class="card group">
                    <div class="flex justify-start items-center gap-2">
                        <IconPay class="bg-[#262626] rounded-full w-6 h-6 p-1" />
                        <span class="text-white text-sm">Waxpeer pay</span>

                        <IconArrow class="arrow group-hover:opacity-100" />
                    </div>

                    <p class="text-[#BABAC2]/50 text-sm ml-8 py-3">The last successful trade</p>

                    <div class="flex justify-end items-center py-6">
                        <span
                            class="bg-gradient-to-b from-white to-transparent bg-clip-text text-transparent text-[30px]">
                            10 sec
                        </span>
                    </div>
                </div>

                <div class="card group">
                    <div class="flex justify-start items-center gap-2">
                        <IconCalendar class="bg-[#20CE70]/10 rounded-full w-6 h-6 p-1" />
                        <span class="text-white text-sm">Availability of a site</span>

                        <IconArrow class="arrow group-hover:opacity-100" />
                    </div>

                    <p class="text-[#BABAC2]/50 text-sm ml-8 py-3">The availability of the home page of the site</p>

                    <div class="flex justify-end items-center py-6">
                        <span class="text-[30px] text-[#20CE70]">
                            available
                        </span>
                    </div>
                </div>

                <div class="card group">
                    <div class="flex justify-start items-center gap-2">
                        <IconCloud class="bg-[#EC7A2A]/10 rounded-full w-6 h-6 p-1" />
                        <span class="text-white text-sm">Server status</span>

                        <IconArrow class="arrow group-hover:opacity-100" />
                    </div>

                    <p class="text-[#BABAC2]/50 text-sm ml-8 py-3">The status of the website servers</p>

                    <div class="flex justify-end items-center py-6">
                        <span class="text-[30px] text-[#EC7A2A]">
                            unstable
                        </span>
                    </div>
                </div>

                <div class="card group">
                    <div class="flex justify-start items-center gap-2">
                        <IconSteam class="bg-[#20CE70]/10 rounded-full w-6 h-6 p-1" />
                        <span class="text-white text-sm">Steam Web API</span>

                        <IconArrow class="arrow group-hover:opacity-100" />
                    </div>

                    <p class="text-[#BABAC2]/50 text-sm ml-8 py-3">Last check June 3, 2022 02:50:16</p>

                    <div class="flex justify-end items-center py-6">
                        <span class="text-[30px] text-[#20CE70]">
                            stable
                        </span>
                    </div>
                </div>

                <div class="card group">
                    <div class="flex justify-start items-center gap-2">
                        <IconSettings class="bg-[#262626] rounded-full w-6 h-6 p-1" />
                        <span class="text-white text-sm">API response</span>

                        <IconArrow class="arrow group-hover:opacity-100" />
                    </div>

                    <p class="text-[#BABAC2]/50 text-sm ml-8 py-3">Last request 10 seconds ago</p>

                    <div class="flex justify-end items-center py-6">
                        <span
                            class="bg-gradient-to-b from-white to-transparent bg-clip-text text-transparent text-[30px]">
                            2.856 ms
                        </span>
                    </div>
                </div>

                <div class="card group">
                    <div class="flex justify-start items-center gap-2">
                        <IconCart class="bg-[#EF5858]/10 rounded-full w-6 h-6 p-1" />
                        <span class="text-white text-sm">Last trade</span>

                        <IconArrow class="arrow group-hover:opacity-100" />
                    </div>

                    <p class="text-[#BABAC2]/50 text-sm ml-8 py-3">The last trade was created 5s ago</p>

                    <div class="flex justify-end items-center py-6">
                        <span class="text-[30px] text-[#EF5858]">
                            canceled
                        </span>
                    </div>
                </div>

                <div class="card group">
                    <div class="flex justify-start items-center gap-2">
                        <IconUser class="bg-[#20CE70]/10 rounded-full w-6 h-6 p-1" />
                        <span class="text-white text-sm">Login</span>

                        <IconArrow class="arrow group-hover:opacity-100" />
                    </div>

                    <p class="text-[#BABAC2]/50 text-sm ml-8 py-3">Shows either your login is working or not</p>

                    <div class="flex justify-end items-center py-6">
                        <span class="text-[30px] text-[#20CE70]">
                            active
                        </span>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>